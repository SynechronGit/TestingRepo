@Library('markel.devops.gamma')_

/*THIS FILE IS UPDATES BY THE DEVOPS TEAM*/
/*Paramteter specific per system*/

/*Handle custom behavior*/
buildTemplate (
customworkspace: 'TRUE',
buildtype: 'dotnet',
action:'',
configuration:'',
platform:'',
updateassemblyinfo:'true',
packagechannel: 'MATS',
packagebasename: 'E2.UnderwritingAPI',
packageformat: '',
websiteproject: 'Components\\E2.Component.Underwriting.API\\E2.Component.Underwriting.API.csproj',
projectparameters: '/t:WebPublish /p:WebPublishMethod=FileSystem',
outputparameter: '/p:publishUrl=',
frameworkparameter: '',
solution: 'e2UnderwritingAPI.sln',
builddirectory: '',
outputdirectory: '',
workingdirectory: '',
buildoptimizers: '',
nugetSources: 'c:\\nuget\\nuget.config',
copy: '',
copylocation: '',
deployproject:'E2.UnderwritingAPI.Site')

/*A parameter can be removed and can be set to null but can not be set to nothing */
/*Valid: packagebasename: 'FAST'*/
/*Valid: packagebasename: '', */
/*Valid: If paramter ommitted*/
/*Not Valid: packagebasename:*/
/*buildtype OPTIONS: MSBUILD,NPM,DOTNET,ZIP*/
/*customworkspace OPTIONS: TRUE, FALSE*/
/*packageformat OPTIONS: ZIP, NUPKG*/
/*builddirectory = msbuild/dotnet build output, npm build starting location, zip that specific folder*/
