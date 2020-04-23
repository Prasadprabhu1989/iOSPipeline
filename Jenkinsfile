
def xcodeproj = 'iOSPipeline.xcodeproj' // Path to the xcodeproj
def xcarchive_name = "iOSPipeline.xcarchive" // Name of the archive to build
def build_scheme = 'iOSPipeline' // Scheme to build the app
def test_scheme = 'iOSPipeline' // Scheme to build tests
def simulator_device = 'iPhone 7' // Name of the device type to use for tests


pipeline {
agent any
stages {
stage('Build') {

xcodeBuild {
xcodeBuild appURL: '', 
assetPackManifestURL: '', 
buildDir: '$(WORKSPACE)/build', 
buildIpa: true, bundleID: '', 
bundleIDInfoPlistPath: '', 
cfBundleShortVersionStringValue: '', 
cfBundleVersionValue: '', 
cleanBeforeBuild: false, 
cleanResultBundlePath: false, 
compileBitcode: false, 
configuration: 'development', 
developmentTeamID: 'ULN4HA5APP', 
developmentTeamName: '', 
displayImageURL: '', 
fullSizeImageURL: '', 
ipaExportMethod: 'development',
 ipaName: '$(VERSION)_$(BUILD_DATE)', 
ipaOutputDirectory: '', keychainId: '', 
keychainPath: '${HOME}/Library/Keychains/login.keychain', 
keychainPwd: hudson.util.Secret.fromString(''), 
logfileOutputDirectory: '', 
provisioningProfiles: [[provisioningProfileAppId: 'com.lockdown.app', provisioningProfileUUID: '4e3f3e97-d9d0-465e-9340-de6a3e0acc30']], 
resultBundlePath: '', sdk: '', signingMethod: 'manual', symRoot: '', target: '', thinning: '', unlockKeychain: true, uploadBitcode: false, uploadSymbols: false, xcodeProjectFile: '', xcodeProjectPath: 'iOSPipeline', xcodeSchema: '', xcodeWorkspaceFile: '', xcodebuildArguments: ''
}
                   } 
     } 

}

