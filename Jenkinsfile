
def xcodeproj = 'iOSPipeline.xcodeproj' // Path to the xcodeproj
def xcarchive_name = "iOSPipeline.xcarchive" // Name of the archive to build
def build_scheme = 'iOSPipeline' // Scheme to build the app
def test_scheme = 'iOSPipeline' // Scheme to build tests
def simulator_device = 'iPhone 7' // Name of the device type to use for tests


pipeline {
agent any
stages {
stage('Build') {
steps {
exportIpa appURL: '',
archiveDir: '${WORKSPACE}/iOSPipeline',
assetPackManifestURL: '',
compileBitcode: false,
developmentTeamID: 'ULN4HA5APP',
developmentTeamName: 'Tregaron India Holdings, LLC',
displayImageURL: '',
fullSizeImageURL: '',
ipaExportMethod: 'development',
ipaName: '${VERSION}_${BUILD_DATE}',
ipaOutputDirectory: '${WORKSPACE}/iOSPipeline',
keychainName: '',
keychainPath:  '${HOME}/Library/Keychains/login.keychain',
keychainPwd: hudson.util.Secret.fromString(''),
packResourcesAsset: true,
provisioningProfiles: [[provisioningProfileAppId: 'com.lockdown.app', provisioningProfileUUID: '4e3f3e97-d9d0-465e-9340-de6a3e0acc30']],
resourcesAssetURL: '',
signingMethod: 'manual',
thinning: '',
unlockKeychain: false,
uploadBitcode: false,
uploadSymbols: false,
xcodeProjectPath: 'iOSPipeline',
xcodeSchema: 'iOSPipeline',
xcodeWorkspaceFile: ''
}
                   } 
     } 

}

