# Change log: 3.8.0 (gpu)

This page lists all package changes since the previous release (3.7.0).

## Direct dependencies

> [!NOTE]
> These packages are explicitly included in the image. Their updates follow SageMaker Distribution's [versioning strategy](https://github.com/aws/sagemaker-distribution#versioning-strategy).

### Changed

Package | Previous Version | Current Version | Change Type
---|---|---|---
jupyterlab|4.4.10|4.5.3|minor
uvicorn|0.38.0|0.40.0|minor
autogluon|1.4.0|1.5.0|minor
notebook|7.4.7|7.5.3|minor
fastapi|0.124.4|0.128.0|minor
mcp|1.23.3|1.25.0|minor
supervisor|4.2.5|4.3.0|minor
amazon-sagemaker-jupyter-ai-q-developer|1.2.8|1.2.9|patch
amazon-sagemaker-jupyter-scheduler|3.1.15|3.1.16|patch
amazon_sagemaker_sql_editor|0.1.19|0.1.20|patch
conda|25.11.0|25.11.1|patch
jupyterlab-git|0.51.3|0.51.4|patch
sagemaker-code-editor|1.8.0|1.8.2|patch
sagemaker-gen-ai-jupyterlab-extension|1.0.11|1.0.13|patch
sagemaker-studio|1.1.4|1.1.5|patch
sagemaker-studio-analytics-extension|0.2.2|0.2.4|patch
sagemaker-studio-dataengineering-extensions|1.3.3|1.3.4|patch
sagemaker-studio-dataengineering-sessions|1.3.11|1.3.12|patch
uv|0.9.17|0.9.27|patch

### New

Package | Version
---|---
langchain-openai|0.3.35

## Indirect dependencies

> [!NOTE]
> These packages are pulled in automatically to satisfy the requirements of the direct dependencies. Their versions may vary between releases.

### Changed

Package | Previous Version | Current Version | Change Type
---|---|---|---
ca-certificates|2025.11.12|2026.1.4|major
certifi|2025.11.12|2026.1.4|major
rdma-core|60.0|61.0|major
send2trash|1.8.3|2.1.0|major
dask-core|2025.12.0|2026.1.1|major
distributed|2025.12.0|2026.1.1|major
regex|2025.11.3|2026.1.15|major
svt-av1|3.1.2|4.0.0|major
xorg-xorgproto|2024.1|2025.1|major
pathspec|0.12.1|1.0.3|major
black|25.12.0|26.1.0|major
websockets|15.0.1|16.0|major
readline|8.2|8.3|minor
absl-py|2.3.1|2.4.0|minor
nccl|2.28.9.1|2.29.2.1|minor
setuptools|80.9.0|80.10.2|minor
libcurl|8.17.0|8.18.0|minor
aioitertools|0.12.0|0.13.0|minor
jmespath|1.0.1|1.1.0|minor
tomli|2.3.0|2.4.0|minor
alembic|1.17.2|1.18.1|minor
rpds-py|0.30.0|0.27.1|minor
narwhals|2.13.0|2.15.0|minor
async-lru|2.0.5|2.1.0|minor
wcwidth|0.2.14|0.5.0|minor
jupyter_client|8.7.0|8.8.0|minor
mistune|3.1.4|3.2.0|minor
prometheus_client|0.23.1|0.24.1|minor
json5|0.12.1|0.13.0|minor
uuid-utils|0.12.0|0.13.0|minor
langsmith|0.4.59|0.6.5|minor
wheel|0.45.1|0.46.3|minor
pyathena|3.22.0|3.25.0|minor
tomlkit|0.13.3|0.14.0|minor
fastcore|1.8.17|1.12.5|minor
autogluon.common|1.4.0|1.5.0|minor
lcms2|2.17|2.18|minor
pyparsing|3.2.5|3.3.2|minor
google-auth|2.43.0|2.48.0|minor
proto-plus|1.26.1|1.27.0|minor
google-api-core|2.28.1|2.29.0|minor
virtualenv|20.35.4|20.36.1|minor
autogluon.core|1.4.0|1.5.0|minor
autogluon.features|1.4.0|1.5.0|minor
rich|14.2.0|14.3.1|minor
lightning|2.6.0|2.5.6|minor
autogluon.multimodal|1.4.0|1.5.0|minor
fastprogress|1.0.3|1.1.3|minor
typer-slim|0.20.0|0.21.1|minor
typer-slim-standard|0.20.0|0.21.1|minor
typer|0.20.0|0.21.1|minor
autogluon.tabular|1.4.0|1.5.0|minor
optuna|4.6.0|4.7.0|minor
autogluon.timeseries|1.4.0|1.5.0|minor
awswrangler|3.14.0|3.15.0|minor
pytokens|0.3.0|0.4.0|minor
databricks-sdk|0.74.0|0.73.0|minor
uvicorn-standard|0.38.0|0.40.0|minor
fastapi-core|0.124.4|0.128.0|minor
google-api-core-grpc|2.28.1|2.29.0|minor
google-crc32c|1.7.1|1.8.0|minor
google-cloud-bigquery-core|3.38.0|3.40.0|minor
sse-starlette|3.0.4|3.2.0|minor
termcolor|3.2.0|3.3.0|minor
llvm-openmp|21.1.7|21.1.8|patch
liblzma|5.8.1|5.8.2|patch
libuuid|2.41.2|2.41.3|patch
openssl|3.6.0|3.6.1|patch
filelock|3.20.0|3.20.3|patch
libpng|1.6.53|1.6.54|patch
xorg-libxext|1.3.6|1.3.7|patch
aiohttp|3.13.2|3.13.3|patch
greenlet|3.3.0|3.3.1|patch
sqlalchemy|2.0.45|2.0.46|patch
alsa-lib|1.2.14|1.2.15.3|patch
anyio|4.12.0|4.12.1|patch
debugpy|1.8.18|1.8.19|patch
tornado|6.5.3|6.5.4|patch
jupyter_server_terminals|0.5.3|0.5.4|patch
soupsieve|2.8|2.8.3|patch
nbclient|0.10.2|0.10.4|patch
orjson|3.11.4|3.11.5|patch
langchain-core|0.3.79|0.3.81|patch
sagemaker-jupyterlab-extension-common|0.2.15|0.2.16|patch
dill|0.4.0|0.4.1|patch
multiprocess|0.70.18|0.70.19|patch
transformers|4.57.3|4.57.6|patch
scramp|1.4.6|1.4.8|patch
astroid|4.0.2|4.0.3|patch
joblib|1.5.2|1.5.3|patch
xorg-libxrandr|1.5.4|1.5.5|patch
xorg-libxxf86vm|1.1.6|1.1.7|patch
pyasn1|0.6.1|0.6.2|patch
setproctitle|1.3.6|1.3.7|patch
gdown|5.2.0|5.2.1|patch
markdown|3.10|3.10.1|patch
libaec|1.1.4|1.1.5|patch
werkzeug|3.1.4|3.1.5|patch
xorg-libxinerama|1.1.5|1.1.6|patch
python-multipart|0.0.20|0.0.22|patch
plum-dispatch|2.6.0|2.6.1|patch
fastai|2.8.5|2.8.6|patch
fugue|0.9.3|0.9.4|patch
bokeh|3.8.1|3.8.2|patch
ruamel.yaml.clib|0.2.14|0.2.15|patch
ruamel.yaml|0.18.16|0.18.17|patch
truststore|0.10.3|0.10.4|patch
coverage|7.13.0|7.13.2|patch
pynacl|1.6.1|1.6.2|patch
rich-toolkit|0.17.0|0.17.1|patch
fastapi-cli|0.0.16|0.0.20|patch
gitpython|3.1.45|3.1.46|patch
pycrdt|0.12.44|0.12.45|patch
jupyter_ydoc|3.3.3|3.3.4|patch
nbdime|4.0.2|4.0.3|patch
panel|1.8.4|1.8.7|patch
pox|0.3.6|0.3.7|patch
ppft|1.7.7|1.7.8|patch
pathos|0.3.4|0.3.5|patch
pymssql|2.3.10|2.3.11|patch

### New

Package | Version
---|---
pycalverter|1.6.1
sqlite|3.48.0
apsw|3.48.0.0
apswutils|0.1.2
fastlite|0.2.3
oauthlib|3.3.1
python-fasthtml|0.12.39
pydantic-extra-types|2.11.0
jiter|0.12.0
openai|1.109.1
tiktoken|0.12.0
pydynamodb|0.8.1
