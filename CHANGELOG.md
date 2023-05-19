# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2023-01-08
### Added
- Versión inicial de código.

# Añadido por Javier Guillén el 11-05-2023

# Se modifica archivo src/requirements.txt determinando versión de librerías 'urllib3<2'

# samconfig.toml - añado parámetros en 
# staging]
# [staging.deploy]
# [staging.deploy.parameters]

confirm_changeset = true
s3_bucket = "aws-sam-cli-managed-default-samclisourcebucket-1tp93onkchp8k"


# Modificación todoApiTest.py:
BASE_URL = os.environ.get("BASE_URL")
#BASE_URL = "https://m0qwfec693.execute-api.us-east-1.amazonaws.com/Prod"

BASE_URL = os.environ.get("BASE_URL")
BASE_URL = "https://ds2wk9e4jg.execute-api.us-east-1.amazonaws.com/Prod"

# Modificación todoApiTest.py2:
BASE_URL = os.environ.get("https://ds2wk9e4jg.execute-api.us-east-1.amazonaws.com/Prod")
#BASE_URL = "https://ds2wk9e4jg.execute-api.us-east-1.amazonaws.com/Prod"