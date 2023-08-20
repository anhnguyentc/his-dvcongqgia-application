def zipPath = "C:\\Program Files\\7-Zip\\7z.exe"
def packagePathService = "C:\\IT-VCBS\\BONPublish\\WEB\\"
def workspace = "C:\\Jenkins\\workspace"
def MSBUILD = "C:\\Jenkins\\lib\\MSBuild\\14.0\\Bin\\"

node{
	agent any
		environment{
			REPO_PATH="C:\\Program Files\\Jenkins"
			APP_NAME='test'
		}
		
	stage("Checkout SCM"){
		cleanWs()
		checkout scm
	}

}