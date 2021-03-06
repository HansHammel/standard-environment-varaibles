# standard-environment-varaibles
A list of commonly used (standard) envronment variables 

| Name | default value | possible values/ samples | used by | description | conflicts |
|----------------------------------------------------|---------------|------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| CAMPFIRE_TOKEN |  |  |  |  |  |
| DATABASE_URL |  |  |  |  |  |
| MONGO_URL |  |  |  |  |  |
| MONGO_URL |  |  |  |  |  |
| MONGODB_URL |  |  |  |  |  |
| MONGOHQ_URL |  |  |  |  |  |
| MYSQL_DATABASE |  |  |  |  |  |
| MYSQL_HOST | localhost |  |  |  |  |
| MYSQL_PASSWORD |  |  |  |  |  |
| MYSQL_USER |  |  |  |  |  |
| NODE_CONFIG |  |  |  |  |  |
| NODE_ENV |  | development, test, production | node.js |  |  |
| OPENSHIFT_REDIS_HOST |  |  |  |  |  |
| OPENSHIFT_REDIS_PORT |  |  |  |  |  |
| REDIS_AUTH |  |  |  |  |  |
| REDIS_DB |  |  |  |  |  |
| REDIS_HOST |  |  |  |  |  |
| REDIS_PASSWORD |  |  |  |  |  |
| REDIS_PORT |  |  |  |  |  |
| REDIS_UR |  | =redis://rediscloud:password@host:port |  |  |  |
| REDIS_URL |  |  |  |  |  |
| REDIS_URL |  |  |  |  |  |
| REDISTOGO_URL |  |  |  |  |  |
| SELENIUM_RC_HOST |  |  |  |  |  |
| SOLR_URL |  |  |  |  |  |
| USE_NETWORK |  |  |  |  |  |
| VCAP_SERVICES |  |  |  |  |  |
|  |  |  |  |  |  |
| CI |  |  | Gitlab | Mark that build is executed in CI environment |  |
| GITLAB_CI |  |  | Gitlab | Mark that build is executed in GitLab CI environment |  |
| CI_SERVER |  |  | Gitlab | Mark that build is executed in CI environment |  |
| CI_SERVER_NAME |  |  | Gitlab | The name of CI server that is used to coordinate builds |  |
| CI_SERVER_VERSION |  |  | Gitlab | GitLab version that is used to schedule builds |  |
| CI_SERVER_REVISION |  |  | Gitlab | GitLab revision that is used to schedule builds |  |
| CI_BUILD_ID |  |  | Gitlab | The unique id of the current build that GitLab CI uses internally |  |
| CI_BUILD_REF |  |  | Gitlab | The commit revision for which project is built |  |
| CI_BUILD_TAG |  |  | Gitlab | The commit tag name. Present only when building tags. |  |
| CI_BUILD_NAME |  |  | Gitlab | The name of the build as defined in .gitlab-ci.yml |  |
| CI_BUILD_STAGE |  |  | Gitlab | The name of the stage as defined in .gitlab-ci.yml |  |
| CI_BUILD_REF_NAME |  |  | Gitlab | The branch or tag name for which project is built |  |
| CI_BUILD_REF_SLUG |  |  | Gitlab | $CI_BUILD_REF_NAME lowercased, shortened to 63 bytes, and with everything except 0-9 and a-z replaced with -. Use in URLs and domain names. |  |
| CI_BUILD_REPO |  |  | Gitlab | The URL to clone the Git repository |  |
| CI_BUILD_TRIGGERED |  |  | Gitlab | The flag to indicate that build was triggered |  |
| CI_BUILD_MANUAL |  |  | Gitlab | The flag to indicate that build was manually started |  |
| CI_BUILD_TOKEN |  |  | Gitlab | Token used for authenticating with the GitLab Container Registry |  |
| CI_PIPELINE_ID |  |  | Gitlab | The unique id of the current pipeline that GitLab CI uses internally |  |
| CI_PROJECT_ID |  |  | Gitlab | The unique id of the current project that GitLab CI uses internally |  |
| CI_PROJECT_NAME |  |  | Gitlab | The project name that is currently being built |  |
| CI_PROJECT_NAMESPACE |  |  | Gitlab | The project namespace (username or groupname) that is currently being built |  |
| CI_PROJECT_PATH |  |  | Gitlab | The namespace with project name |  |
| CI_PROJECT_URL |  |  | Gitlab | The HTTP address to access project |  |
| CI_PROJECT_DIR |  |  | Gitlab | The full path where the repository is cloned and where the build is run |  |
| CI_ENVIRONMENT_NAME |  |  | Gitlab | The name of the environment for this build |  |
| CI_ENVIRONMENT_SLUG |  |  | Gitlab | A simplified version of the environment name, suitable for inclusion in DNS, URLs, Kubernetes labels, etc. |  |
| CI_REGISTRY |  |  | Gitlab | If the Container Registry is enabled it returns the address of GitLab's Container Registry |  |
| CI_REGISTRY_IMAGE |  |  | Gitlab | If the Container Registry is enabled for the project it returns the address of the registry tied to the specific project |  |
| CI_RUNNER_ID |  |  | Gitlab | The unique id of runner being used |  |
| CI_RUNNER_DESCRIPTION |  |  | Gitlab | The description of the runner as saved in GitLab |  |
| CI_RUNNER_TAGS |  |  | Gitlab | The defined runner tags |  |
| CI_DEBUG_TRACE |  |  | Gitlab | Whether debug tracing is enabled |  |
| GITLAB_USER_ID |  |  | Gitlab | The id of the user who started the build |  |
| GITLAB_USER_EMAIL |  |  | Gitlab | The email of the user who started the build |  |
|  |  |  |  |  |  |
| PGHOST |  |  | PostgresQL | behaves the same as host connection parameter. |  |
| PGHOSTADDR |  |  | PostgresQL | behaves the same as hostaddr connection parameter. This can be set instead of or in addition to PGHOST to avoid DNS lookup overhead. |  |
| PGPORT |  |  | PostgresQL | behaves the same as port connection parameter. |  |
| PGDATABASE |  |  | PostgresQL | behaves the same as dbname connection parameter. |  |
| PGUSER |  |  | PostgresQL | behaves the same as user connection parameter. database. |  |
| PGPASSWORD |  |  | PostgresQL | behaves the same as password connection parameter. Use of this environment variable is not recommended for security reasons (some operating systems allow non-root users to see process environment variables via ps); instead consider using the ~/.pgpass file (see Section 30.14). |  |
| PGPASSFILE |  |  | PostgresQL | specifies the name of the password file to use for lookups. If not set, it defaults to ~/.pgpass (see Section 30.14). |  |
| PGSERVICE |  |  | PostgresQL | behaves the same as service connection parameter. |  |
| PGREALM |  |  | PostgresQL | sets the Kerberos realm to use with PostgreSQL, if it is different from the local realm. If PGREALM is set, libpq applications will attempt authentication with servers for this realm and use separate ticket files to avoid conflicts with local ticket files. This environment variable is only used if Kerberos authentication is selected by the server. |  |
| PGOPTIONS |  |  | PostgresQL | behaves the same as options connection parameter. |  |
| PGSSLMODE |  |  | PostgresQL | behaves the same as sslmode connection parameter. |  |
| PGREQUIRESSL |  |  | PostgresQL | behaves the same as requiressl connection parameter. |  |
| PGSSLCERT |  |  | PostgresQL | behaves the same as sslcert connection parameter. |  |
| PGSSLKEY |  |  | PostgresQL | behaves the same as sslkey connection parameter. |  |
| PGSSLROOTCERT |  |  | PostgresQL | behaves the same as sslrootcert connection parameter. |  |
| PGSSLCRL |  |  | PostgresQL | behaves the same as sslcrl connection parameter. |  |
| PGKRBSRVNAME |  |  | PostgresQL | behaves the same as krbsrvname connection parameter. |  |
| PGGSSLIB |  |  | PostgresQL | behaves the same as gsslib connection parameter. |  |
| PGCONNECT_TIMEOUT |  |  | PostgresQL | behaves the same as connect_timeout connection parameter. |  |
| PGDATESTYLE |  |  | PostgresQL | sets the default style of date/time representation. (Equivalent to SET datestyle TO ....) |  |
| PGTZ |  |  | PostgresQL | sets the default time zone. (Equivalent to SET timezone TO ....) |  |
| PGCLIENTENCODING |  |  | PostgresQL | sets the default client character set encoding. (Equivalent to SET client_encoding TO ....) |  |
| PGGEQO |  |  | PostgresQL | sets the default mode for the genetic query optimizer. (Equivalent to SET geqo TO ....) |  |
| PGSYSCONFDIR |  |  | PostgresQL | sets the directory containing the pg_service.conf file. |  |
| PGLOCALEDIR |  |  | PostgresQL | sets the directory containing the locale files for message internationalization. |  |
|  |  |  |  |  |  |
| OpenShift |  |  |  |  |  |
| OS_USERNAME |  |  | OpenShift |  |  |
| OS_PASSWORD |  |  | OpenShift |  |  |
| OS_TENANT_NAME |  |  | OpenShift |  |  |
| OS_AUTH_URL |  |  | OpenShift |  |  |
|  |  |  |  |  |  |
| OS_TENANT_ID=tenantIDString |  |  | OpenShift |  |  |
| OS_REGION_NAME=regionName |  |  | OpenShift |  |  |
| OS_CACERT=/path/to/cacertFile |  |  | OpenShift |  |  |
|  |  |  |  |  |  |
| OPENSHIFT_APP_DNS |  |  | OpenShift | The fully-qualified domain namespace of the application. |  |
| OPENSHIFT_APP_NAME |  |  | OpenShift | The name of the application. |  |
| OPENSHIFT_APP_UUID |  |  | OpenShift | The UUID of the application (32 hexadecimal characters). |  |
| OPENSHIFT_<cart-name>_IP |  |  | OpenShift | The IP address the application listens on. |  |
| OPENSHIFT_<cart-name>_PORT |  |  | OpenShift | The port the application receives requests from. |  |
| OPENSHIFT_SECRET_TOKEN |  |  | OpenShift | A 128-character string unique to an application that can be used for authentication, and can be overridden with the rhc env set command. |  |
| OPENSHIFT_HOMEDIR |  |  | OpenShift | The home directory of the application. |  |
| OPENSHIFT_DATA_DIR |  |  | OpenShift | A persistent data directory. |  |
| OPENSHIFT_REPO_DIR |  |  | OpenShift | Repository containing the currently deployed version of the application. |  |
| OPENSHIFT_TMP_DIR |  |  | OpenShift | A temporary directory you can use; SELinux protects data in this directory from other users. |  |
| OPENSHIFT_LOG_DIR |  |  | OpenShift | Where all cartridge logs are stored. |  |
| LOGSHIFTER_PHP_MAX_FILESIZE=500K |  |  | OpenShift |  |  |
| LOGSHIFTER_PHP_MAX_FILESIZE=10M |  |  | OpenShift |  |  |
| LOGSHIFTER_PHP_MAX_FILESIZE=2G |  |  | OpenShift |  |  |
| LOGSHIFTER_PHP_MAX_FILESIZE=1T |  |  | OpenShift |  |  |
| OPENSHIFT_<database>_DB_HOST |  |  | OpenShift | The host name or IP address used to connect to the database. |  |
| OPENSHIFT_<database>_DB_PORT |  |  | OpenShift | The port the database server is listening on. |  |
| OPENSHIFT_<database>_DB_USERNAME |  |  | OpenShift | The database administrative user name. |  |
| OPENSHIFT_<database>_DB_PASSWORD |  |  | OpenShift | The database administrative user?s password. |  |
| OPENSHIFT_<database>_DB_SOCKET |  |  | OpenShift | An AF socket for connecting to the database (for non-scaled apps only). |  |
| OPENSHIFT_<database>_DB_URL |  |  | OpenShift | Database connection URL. |  |
| OPENSHIFT_MAX_SESSIONS_PER_GEAR |  |  | OpenShift | Configures the max sessions used for the scaling algorithm |  |
| OPENSHIFT_<cart-name>_LD_LIBRARY_PATH_ELEMENT |  |  | OpenShift | Configures the location of each cartridge?s library file. |  |
| JENKINS_USERNAME |  |  | OpenShift | System builder account on the Jenkins server. |  |
| JENKINS_PASSWORD |  |  | OpenShift | Password for the system builder account on the Jenkins server. |  |
| JENKINS_URL |  |  | OpenShift | DNS name for the associated Jenkins server where builds occur. |  |
| JAVA_OPTS_EXT |  |  | OpenShift | Appended to JAVA_OPTS prior to invoking the Java VM. |  |
| OPENSHIFT_GEAR_DNS |  |  | OpenShift | The fully-qualified domain name of the gear. |  |
| OPENSHIFT_GEAR_NAME |  |  | OpenShift | The name of the gear. |  |
| OPENSHIFT_GEAR_UUID |  |  | OpenShift | The UUID of the gear. |  |
|  |  |  |  |  |  |
| TRAVIS |  |  | TravisCI |  |  |
| TRAVIS_OS_NAME |  |  | TravisCI |  |  |
| TRAVIS_BUILD_DIR |  |  | TravisCI |  |  |
| TRAVIS_REPO_SLUG |  |  | TravisCI |  |  |
| TRAVIS_COMMIT_RANGE |  |  | TravisCI |  |  |
| TRAVIS_BUILD_NUMBER |  |  | TravisCI |  |  |
| TRAVIS_JOB_NUMBER |  |  | TravisCI |  |  |
| TRAVIS_BUILD_ID |  |  | TravisCI |  |  |
| TRAVIS_JOB_ID |  |  | TravisCI |  |  |
| TRAVIS_BRANCH |  |  | TravisCI |  |  |
| TRAVIS_COMMIT |  |  | TravisCI |  |  |
| TRAVIS_PULL_REQUEST |  |  | TravisCI |  |  |
| TRAVIS_NODE_VERSION |  |  | TravisCI |  |  |
| TRAVIS_PHP_VERSION |  |  | TravisCI |  |  |
| TRAVIS_PYTHON_VERSION |  |  | TravisCI |  |  |
| TRAVIS_RUBY_VERSION |  |  | TravisCI |  |  |
| TRAVIS_SCALA_VERSION |  |  | TravisCI |  |  |
|  |  |  |  |  |  |
| BASE_BRANCH |  |  | Shippable | Name of the target branch into which the pull request changes will be merged. |  |
| BRANCH |  |  | Shippable | Name of branch being built. |  |
| BUILD_NUMBER |  |  | Shippable | Build number for current build. |  |
| BUILD_URL |  |  | Shippable | Direct URL link to the build output. |  |
| CACHE_CONTAINER |  |  | Shippable | false |  |
| CACHE_DIR |  |  | Shippable | If cache is true in the build section of shippable.yml, then true. Otherwise false. |  |
| CI |  |  | Shippable | true |  |
| COMMIT |  |  | Shippable | Commit id that is being built and tested. |  |
| COMMITTER |  |  | Shippable | Name of the last committer. |  |
| COMMIT_MESSAGE |  |  | Shippable | Commit message specified in the commit. |  |
| COMPARE_URL |  |  | Shippable | A link to GitHub/Bitbucket's comparision view for the push. |  |
| CONTINUOUS_INTEGRATION |  |  | Shippable | true |  |
| DEBIAN_FRONTEND |  |  | Shippable | noninteractive |  |
| HEAD_BRANCH |  |  | Shippable | This is only set for pull requests and is the name of the branch the pull request was opened from. |  |
| IS_PULL_REQUEST |  |  | Shippable | Set to true if the job is a pull request. If not, this will be set to false. |  |
| IS_FORK |  |  | Shippable | Set to true if the job belongs to a forked project. If not, this will be set to false. |  |
| JOB_ID |  |  | Shippable | ID of job in Shippable. |  |
| JOB_NUMBER, SHIPPABLE_JOB_NUMBER, SHIPPABLE_JOB_ID |  |  | Shippable | All three variables are the same & represent the number of the job in Shippable. |  |
| LANG |  |  | Shippable | en_US.UTF-8 |  |
| LAST_AUTHOR |  |  | Shippable | Name of the last author. |  |
| LAST_SUCCESSFUL_BUILD_TIMESTAMP |  |  | Shippable | Timestamp of the last successful build in seconds. This will be set to false for the first build or for the build with no prior successful builds. |  |
| LC_ALL |  |  | Shippable | en_US.UTF-8 |  |
| LC_CTYPE |  |  | Shippable | en_US.UTF-8 |  |
| MERB_ENV |  |  | Shippable | test |  |
| ORG_NAME |  |  | Shippable | Name of the organization/user that owns the repository currently being built (eg. This will be set to Shippable if the full name is Shippable/support). |  |
| PATH |  |  | Shippable | $HOME/bin:$PATH:$HOME/usr/local/bin |  |
| PROJECT_ID |  |  | Shippable | ID of the Shippable Project. |  |
| PULL_REQUEST |  |  | Shippable | Pull request number if the job is a pull request. If not, this will be set to false. |  |
| PULL_REQUEST_BASE_BRANCH |  |  | Shippable | Name of the branch that the pull request will be merged into. It should be the same as BASE_BRANCH. |  |
| RACK_ENV |  |  | Shippable | test |  |
| RAILS_ENV |  |  | Shippable | test |  |
| REPO_FULL_NAME |  |  | Shippable | Full name of the repository currently being built (eg. Shippable/support). |  |
| REPO_NAME |  |  | Shippable | Name of the repository currently being built (eg. This will be set to support if the full name is Shippable/support). |  |
| REPOSITORY_URL |  |  | Shippable | URL of your GitHub or Bitbucket repository. |  |
| SERVICE_SKIP |  |  | Shippable | false |  |
| SHIPPABLE |  |  | Shippable | true |  |
| SHIPPABLE_ARCHIVE |  |  | Shippable | true |  |
| SHIPPABLE_BUILD_DIR |  |  | Shippable | Directory where the repository is cloned. |  |
| SHIPPABLE_BUILD_ID |  |  | Shippable | ID of build in Shippable. |  |
| SHIPPABLE_BUILD_NUMBER |  |  | Shippable | Build number for current build. |  |
| SHIPPABLE_BUNDLER_ARGS |  |  | Shippable | The value of bundler_args in the build section of shippable.yml. |  |
| SHIPPABLE_COMMIT_RANGE |  |  | Shippable | Parent commit? current commit being built. |  |
| SHIPPABLE_DATA_DIR |  |  | Shippable | $HOME/data |  |
| SHIPPABLE_GEMFILE |  |  | Shippable | The gemfile specified for the job in the shippable.yml. |  |
| SHIPPABLE_GO_VERSION |  |  | Shippable | GO version specified for the job. |  |
| SHIPPABLE_GOPATH |  |  | Shippable | PATH set to $HOME |  |
| SHIPPABLE_JDK_VERSION |  |  | Shippable | The jdk for the job in the shippable.yml. |  |
| SHIPPABLE_LEIN_VERSION |  |  | Shippable | Clojure version specified for the job. |  |
| SHIPPABLE_MYSQL_BINARY |  |  | Shippable | /usr/bin/mysqld_safe |  |
| SHIPPABLE_MYSQL_CMD |  |  | Shippable | \$SHIPPABLE_MYSQL_BINARY |  |
| SHIPPABLE_NODE_VERSION |  |  | Shippable | NodeJS version specified for the job. |  |
| SHIPPABLE_OS_NAME |  |  | Shippable | linux |  |
| SHIPPABLE_PHP_VERSION |  |  | Shippable | PHP version specified for the job. |  |
| SHIPPABLE_POSTGRES_VERSION |  |  | Shippable | 09. Feb |  |
| SHIPPABLE_POSTGRES_BINARY |  |  | Shippable | /usr/lib/postgresql/\$SHIPPABLE_POSTGRES_VERSION/bin/postgres |  |
| SHIPPABLE_POSTGRES_CMD |  |  | Shippable | sudo -u postgres \$SHIPPABLE_POSTGRES_BINARY -c config_file=/etc/postgresql/\$SHIPPABLE_POSTGRES_VERSION/main/postgresql.conf"" |  |
| SHIPPABLE_PYTHON_VERSION |  |  | Shippable | Python version specified for the job. |  |
| SHIPPABLE_REPO_DIR |  |  | Shippable | The directory where builds run. |  |
| SHIPPABLE_REPO_SLUG |  |  | Shippable | Full name of the repository being built (e.g. Shippable/support). |  |
| SHIPPABLE_RUBY |  |  | Shippable | Ruby version version specified for the job. |  |
| SHIPPABLE_SCALA_VERSION |  |  | Shippable | Scala version specified for the job. |  |
| SHIPPABLE_SELENIUM_PORT |  |  | Shippable | 4444 |  |
| SHIPPABLE_SELENIUM_BINARY |  |  | Shippable | Location of selenium binary. It is set only if selenium is in the addons or services in the shippable.yml. |  |
| SHIPPABLE_SUBMODULE_ENABLED |  |  | Shippable | Whether or not submodules in the repository will be updated. |  |
| SHIPPABLE_VE_DIR |  |  | Shippable | \$HOME/build_ve/python/2.7 |  |
| SUBSCRIPTION_ID |  |  | Shippable | ID of the Subscription. |  |
| IS_GIT_TAG |  |  | Shippable | Set to true if the build is triggered by a git tag push webhook. If not, this will be set to false. This env variable is currently supported for GitHub only. |  |
| GIT_TAG_NAME |  |  | Shippable | The git tag name if the build is triggered by a git tag push webhook or a release webhook. This env variable is currently supported for GitHub only. |  |
| IS_RELEASE |  |  | Shippable | Set to true if the build is triggered by a release webhook. If not, this will be set to false. This env variable is currently supported for GitHub only. |  |
| IS_PRERELEASE |  |  | Shippable | Set to true if the release is marked pre-release when it was published. If not, this will be set to false. This env variable is currently supported for GitHub only. |  |
| RELEASED_AT |  |  | Shippable | The timestamp when the release was published. This env variable is currently supported for GitHub only. |  |
| RELEASE_NAME |  |  | Shippable | The name of the release webhook. This env variable is currently supported for GitHub only. |  |
|  |  |  |  |  |  |
| CIRCLE_NODE_TOTAL |  |  | CircleCI | The total number of nodes across which the current test is running. |  |
| CIRCLE_NODE_INDEX |  |  | CircleCI | The index (0-based) of the current node. |  |
| CIRCLE_BUILD_IMAGE |  |  | CircleCI | The build image this build runs on. |  |
| CIRCLECI |  |  | CircleCI | true |  |
| CI |  |  | CircleCI | true |  |
| CIRCLE_PROJECT_USERNAME |  |  | CircleCI | The username or organization name of the project being tested, i.e. ?foo? in circleci.com/gh/foo/bar/123 |  |
| CIRCLE_PROJECT_REPONAME |  |  | CircleCI | The repository name of the project being tested, i.e. ?bar? in circleci.com/gh/foo/bar/123 |  |
| CIRCLE_BRANCH |  |  | CircleCI | The name of the Git branch being tested, e.g. ?master?, if the build is running for a branch. |  |
| CIRCLE_TAG |  |  | CircleCI | The name of the git tag being tested, e.g. ?release-v1.5.4?, if the build is running for a tag. |  |
| CIRCLE_SHA1 |  |  | CircleCI | The SHA1 of the commit being tested. |  |
| CIRCLE_REPOSITORY_URL |  |  | CircleCI | A link to the homepage for the current repository, for example, https://github.com/circleci/frontend. |  |
| CIRCLE_COMPARE_URL |  |  | CircleCI | A link to GitHub?s comparison view for this push. Not present for builds that are triggered by GitHub pushes. |  |
| CIRCLE_BUILD_URL |  |  | CircleCI | A permanent link to the current build, for example, https://circleci.com/gh/circleci/frontend/933. |  |
| CIRCLE_BUILD_NUM |  |  | CircleCI | The build number, same as in circleci.com/gh/foo/bar/123 |  |
| CIRCLE_PREVIOUS_BUILD_NUM |  |  | CircleCI | The build number of the previous build, same as in circleci.com/gh/foo/bar/123 |  |
| CI_PULL_REQUESTS |  |  | CircleCI | Comma-separated list of pull requests this build is a part of. |  |
| CI_PULL_REQUEST |  |  | CircleCI | If this build is part of only one pull request, its URL will be populated here. If there was more than one pull request, it will contain one of the pull request URLs (picked randomly). |  |
| CIRCLE_ARTIFACTS |  |  | CircleCI | The directory whose contents are automatically saved as build artifacts. |  |
| CIRCLE_USERNAME |  |  | CircleCI | The GitHub login of the user who either pushed the code to GitHub or triggered the build from the UI/API. |  |
| CIRCLE_TEST_REPORTS |  |  | CircleCI | The directory whose contents are automatically processed as JUnit test metadata. |  |
| CIRCLE_PR_USERNAME |  |  | CircleCI | The username of the owner of the fork. |  |
| CIRCLE_PR_REPONAME |  |  | CircleCI | The name of the repository the pull request was submitted from. |  |
| CIRCLE_PR_NUMBER |  |  | CircleCI | The number of the pull request this build forms part of. |  |
|  |  |  |  |  |  |
| CI |  | true | SemaphoreCI |  |  |
| SEMAPHORE |  | true | SemaphoreCI |  |  |
| BRANCH_NAME |  | Eg. master | SemaphoreCI |  |  |
| REVISION |  | Eg. 6375073ec483bd2d949fad188d1ab869 | SemaphoreCI |  |  |
| WKHTMLTOPDF_PATH |  | /usr/local/bin/wkhtmltopdf | SemaphoreCI |  |  |
| SEMAPHORE_PROJECT_DIR |  | Eg. /home/runner/my_app | SemaphoreCI |  |  |
| SEMAPHORE_CACHE_DIR |  | Eg. /home/runner/my_app/.semaphore-cache | SemaphoreCI |  |  |
| SEMAPHORE_PROJECT_HASH_ID |  | Eg. 18670db3bd1c017cb5fc6013bec1d75d3 | SemaphoreCI |  |  |
| SEMAPHORE_PROJECT_NAME |  | Eg. Base-app | SemaphoreCI |  |  |
| SEMAPHORE_BRANCH_ID |  | Eg. 85726 | SemaphoreCI |  |  |
| SEMAPHORE_BUILD_NUMBER |  | Eg. 23 | SemaphoreCI |  |  |
| SEMAPHORE_REPO_SLUG |  | Eg. rastasheep/my_project | SemaphoreCI |  |  |
| SEMAPHORE_THREAD_RESULT |  | Eg. failed | SemaphoreCI |  |  |
| SEMAPHORE_CURRENT_THREAD |  | Eg. 1 | SemaphoreCI |  |  |
| SEMAPHORE_THREAD_COUNT |  | Eg. 4 | SemaphoreCI |  |  |
| SEMAPHORE_TRIGGER_SOURCE |  | Eg. push, manual, api, scheduler | SemaphoreCI |  |  |
| PULL_REQUEST_NUMBER |  | Eg. 121 | SemaphoreCI |  |  |
| SEMAPHORE_DEPLOY_NUMBER |  | Eg. 17 | SemaphoreCI |  |  |
| SEMAPHORE_SERVER_NAME |  | Eg. staging | SemaphoreCI |  |  |
| HEROKU_API_KEY |  | Eg. 12139243 - when deploying to Heroku | SemaphoreCI |  |  |
| LANG |  | en_US.UTF-8 | SemaphoreCI |  |  |
| LC_ALL |  | en_US.UTF-8 | SemaphoreCI |  |  |
| DATABASE_USERNAME |  | runner | SemaphoreCI |  |  |
| DATABASE_NAME_DEVELOPMENT |  | Eg. 18671ad3b3r7bec1d75d3_development | SemaphoreCI |  |  |
| DATABASE_NAME_TEST |  | Eg. 18671ad3b3rVa5fc6017bec1d75d3_test | SemaphoreCI |  |  |
| DATABASE_PASSWORD |  | semaphoredb | SemaphoreCI |  |  |
| DATABASE_MYSQL_USERNAME |  | root | SemaphoreCI |  |  |
| DATABASE_MYSQL_PASSWORD |  | semaphoredb | SemaphoreCI |  |  |
| DATABASE_POSTGRESQL_USERNAME |  | runner | SemaphoreCI |  |  |
| DATABASE_POSTGRESQL_PASSWORD |  | semaphoredb | SemaphoreCI |  |  |
