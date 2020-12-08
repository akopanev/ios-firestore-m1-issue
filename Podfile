# Uncomment this line if you're using Swift
#use_frameworks!

def core
  pod 'Bolts', '1.9.0'
end

$firebase_version = '7.2-M1'
def firebase_sdk
  pod 'Firebase/Core', $firebase_version

  pod 'Firebase/Analytics', $firebase_version
  pod 'Firebase/Crashlytics', $firebase_version
  pod 'Firebase/Performance', $firebase_version
  pod 'Firebase/Auth', $firebase_version
  pod 'Firebase/DynamicLinks', $firebase_version

  pod 'Firebase/Messaging', $firebase_version
  pod 'Firebase/RemoteConfig', $firebase_version
  pod 'Firebase/Storage', $firebase_version
  pod 'Firebase/Functions', $firebase_version

  pod 'Firebase/Firestore', $firebase_version
end

target 'test app' do
  core
  firebase_sdk
end


