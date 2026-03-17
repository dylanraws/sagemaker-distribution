# Change log: 2.14.0 (gpu)

This page lists all package changes since the previous release (2.13.0).

## Direct dependencies

> [!NOTE]
> These packages are explicitly included in the image. Their updates follow SageMaker Distribution's [versioning strategy](https://github.com/aws/sagemaker-distribution#versioning-strategy).

### Changed

Package | Previous Version | Current Version | Change Type
---|---|---|---
sagemaker-jupyterlab-extension-common|0.2.16|0.3.0|minor
uvicorn|0.40.0|0.41.0|minor
fastapi|0.128.0|0.135.1|minor
jupyterlab-git|0.51.4|0.52.0|minor
keras|3.12.0|3.13.2|minor
mcp|1.25.0|1.26.0|minor
python-gssapi|1.10.1|1.11.1|minor
sagemaker-code-editor|1.8.2|1.9.2|minor
sagemaker-python-sdk|2.254.1|2.257.0|minor
sagemaker-studio-analytics-extension|0.2.4|0.3.0|minor
uv|0.9.27|0.10.8|minor
jupyterlab|4.5.3|4.5.5|patch
amazon_sagemaker_sql_editor|0.1.20|0.1.21|patch
amzn-sagemaker-aiops-jupyterlab-extension|1.0.4|1.0.5|patch
notebook|7.5.3|7.5.4|patch
sagemaker-gen-ai-jupyterlab-extension|1.0.13|1.0.14|patch
sagemaker-jupyterlab-extension|0.5.1|0.5.2|patch
sagemaker-studio|1.1.5|1.1.8|patch
sagemaker-studio-dataengineering-extensions|1.3.4|1.3.7|patch
sagemaker-studio-dataengineering-sessions|1.3.12|1.3.13|patch

## Indirect dependencies

> [!NOTE]
> These packages are pulled in automatically to satisfy the requirements of the direct dependencies. Their versions may vary between releases.

### Changed

Package | Previous Version | Current Version | Change Type
---|---|---|---
llvm-openmp|21.1.8|22.1.0|major
libsystemd0|258.3|259.3|major
libudev1|258.3|259.3|major
setuptools|80.10.2|82.0.0|major
virtualenv|20.36.1|21.1.0|major
isort|7.0.0|8.0.1|major
uc-micro-py|1.0.3|2.0.0|major
ca-certificates|2026.1.4|2026.2.25|minor
filelock|3.20.3|3.25.0|minor
certifi|2026.1.4|2026.2.25|minor
optree|0.18.0|0.19.0|minor
mpmath|1.3.0|1.4.0|minor
accelerate|1.12.0|1.13.0|minor
fontconfig|2.15.0|2.17.1|minor
yarl|1.22.0|1.23.0|minor
narwhals|2.15.0|2.17.0|minor
async-lru|2.1.0|2.2.0|minor
wcwidth|0.5.0|0.6.0|minor
platformdirs|4.5.1|4.9.2|minor
ipykernel|7.1.0|7.2.0|minor
tinycss2|1.5.1|1.4.0|minor
nbconvert-core|7.16.6|7.17.0|minor
babel|2.17.0|2.18.0|minor
jsonpath-ng|1.7.0|1.8.0|minor
uuid-utils|0.13.0|0.14.1|minor
langsmith|0.6.5|0.7.14|minor
pydantic-settings|2.12.0|2.13.1|minor
onnxruntime|1.22.2|1.24.2|minor
pyjwt|2.10.1|2.11.0|minor
regex|2026.1.15|2026.2.28|minor
pandoc|3.8.3|3.9|minor
nbconvert-pandoc|7.16.6|7.17.0|minor
nbconvert|7.16.6|7.17.0|minor
pyathena|3.25.0|3.30.0|minor
xkeyboard-config|2.46|2.47|minor
cookiecutter|2.6.0|2.7.1|minor
tabulate|0.9.0|0.10.0|minor
lazy-loader|0.4|0.5|minor
rav1e|0.7.1|0.8.1|minor
libavif16|1.3.0|1.4.0|minor
starlette|0.50.0|0.52.1|minor
plum-dispatch|2.6.1|2.7.1|minor
typer|0.21.1|0.24.0|minor
typer-slim|0.21.1|0.24.0|minor
numba|0.63.1|0.64.0|minor
rich-toolkit|0.17.1|0.19.7|minor
uvicorn-standard|0.40.0|0.41.0|minor
fastapi-core|0.128.0|0.135.1|minor
jiter|0.12.0|0.13.0|minor
linkify-it-py|2.0.3|2.1.0|minor
sse-starlette|3.2.0|3.3.2|minor
papermill|2.6.0|2.7.0|minor
pyiceberg|0.10.0|0.11.1|minor
snowflake-sqlalchemy|1.8.2|1.9.0|minor
slack-sdk|3.39.0|3.40.1|minor
ld_impl_linux-64|2.45|2.45.1|patch
libexpat|2.7.3|2.7.4|patch
cpython|3.11.14|3.11.15|patch
python-gil|3.11.14|3.11.15|patch
charset-normalizer|3.4.4|3.4.5|patch
tqdm|4.67.1|4.67.3|patch
nccl|2.29.2.1|2.29.3.1|patch
triad|1.0.0|1.0.2|patch
libpng|1.6.54|1.6.55|patch
libfreetype6|2.14.1|2.14.2|patch
libfreetype|2.14.1|2.14.2|patch
freetype|2.14.1|2.14.2|patch
xorg-libx11|1.8.12|1.8.13|patch
multidict|6.7.0|6.7.1|patch
greenlet|3.3.1|3.3.2|patch
sqlalchemy|2.0.46|2.0.48|patch
alembic|1.18.1|1.18.4|patch
debugpy|1.8.19|1.8.20|patch
parso|0.8.5|0.8.6|patch
dask-core|2026.1.1|2026.1.2|patch
distributed|2026.1.1|2026.1.2|patch
orjson|3.11.5|3.11.7|patch
tenacity|9.1.2|9.1.4|patch
python-dotenv|1.2.1|1.2.2|patch
cryptography|46.0.3|46.0.5|patch
fastcore|1.12.5|1.12.23|patch
astroid|4.0.3|4.0.4|patch
expat|2.7.3|2.7.4|patch
unicodedata2|17.0.0|17.0.1|patch
xorg-libxcomposite|0.4.6|0.4.7|patch
proto-plus|1.27.0|1.27.1|patch
smart_open|7.5.0|7.5.1|patch
rich|14.3.1|14.3.3|patch
lightning-utilities|0.15.2|0.15.3|patch
pytorch-lightning|2.6.0|2.6.1|patch
nltk|3.9.2|3.9.3|patch
markdown|3.10.1|3.10.2|patch
charls|2.4.2|2.4.3|patch
svt-av1|4.0.0|4.0.1|patch
werkzeug|3.1.5|3.1.6|patch
catboost|1.2.8|1.2.10|patch
python-fasthtml|0.12.39|0.12.47|patch
smart-open|7.5.0|7.5.1|patch
fastai|2.8.6|2.8.7|patch
fugue|0.9.4|0.9.7|patch
awswrangler|3.15.0|3.15.1|patch
binutils_impl_linux-64|2.45|2.45.1|patch
binutils|2.45|2.45.1|patch
binutils_linux-64|2.45|2.45.1|patch
pathspec|1.0.3|1.0.4|patch
pytokens|0.4.0|0.4.1|patch
coverage|7.13.2|7.13.4|patch
flask|3.1.2|3.1.3|patch
python-duckdb|1.4.3|1.4.4|patch
duckdb|1.4.3|1.4.4|patch
fastapi-cli|0.0.20|0.0.23|patch
freetds|1.5.10|1.5.11|patch
google-cloud-bigquery-core|3.40.0|3.40.1|patch
graphql-core|3.2.7|3.2.8|patch
pycrdt|0.12.45|0.12.47|patch
sqlite-anyio|0.2.3|0.2.8|patch
jupyter-docprovider|2.2.0|2.2.1|patch
nbdime|4.0.3|4.0.4|patch
mmh3|5.2.0|5.2.1|patch
param|2.3.1|2.3.2|patch
panel|1.8.7|1.8.9|patch
pylint|4.0.4|4.0.5|patch
pymssql|2.3.11|2.3.13|patch
sagemaker-core|1.0.67|1.0.76|patch

### New

Package | Version
---|---
arro3-core|0.8.0
python-discovery|1.1.0
conda-gcc-specs|13.4.0
deltalake|1.3.2

### Removed

Package | Last Version
---|---
appdirs|1.4.4
fs|2.4.16
ansicolors|1.1.8
typer-slim-standard|0.21.1
jupyter-server-mathjax|0.2.6
