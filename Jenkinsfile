@Library('ansible-lib') _

def props = readProperties file: 'config.properties'

ansibleDeploy(

    REPO_URL: 'https://github.com/<your-username>/ansible-demo-project.git',

    SLACK_CHANNEL_NAME: props.SLACK_CHANNEL_NAME,

    ENVIRONMENT: props.ENVIRONMENT,

    CODE_BASE_PATH: props.CODE_BASE_PATH,

    ACTION_MESSAGE: props.ACTION_MESSAGE,

    KEEP_APPROVAL_STAGE: props.KEEP_APPROVAL_STAGE
)
