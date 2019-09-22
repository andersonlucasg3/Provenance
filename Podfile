workspace './Provenance'

platform :tvos, '13.0'
use_frameworks!

def all_pods

  pod 'CocoaLumberjack'
  pod 'CocoaLumberjack/Swift'
  pod 'RxRelay'
  pod 'RxRealm'
  pod 'RxCocoa'
  pod 'RealmSwift'
  pod 'HockeySDK-tvOS'
  pod 'CocoaLumberjack/Swift'
  pod 'SteamController'
  pod 'QuickTableViewController'
  pod 'ReachabilitySwift'
  pod 'Crashlytics'
  pod 'ZipArchive'
  pod 'ZIPFoundation'
  pod 'SSZipArchive'
  pod 'SwiftyUserDefaults'
  pod 'SQLite.swift'
  pod 'NSLogger'
  pod 'Differentiator'

end

target 'ProvenanceTV' do
  all_pods
end

target 'PVSupport-tvOS' do
  project './PVSupport/PVSupport'
  
  pod 'CocoaLumberjack'
  pod 'CocoaLumberjack/Swift'
  pod 'NSLogger'
end

target 'PVLibrary-tvOS' do
  project './PVLibrary/PVLibrary'
  
  pod 'CocoaLumberjack'
  pod 'CocoaLumberjack/Swift'
  pod 'RealmSwift'
  pod 'RxCocoa'
  pod 'RxRealm'
  pod 'SQLite.swift'
  pod 'ZipArchive'
  pod 'ZIPFoundation'
  pod 'SSZipArchive'
end

target 'TopShelf' do
  pod 'CocoaLumberjack'
  pod 'CocoaLumberjack/Swift'
  pod 'RealmSwift'
end