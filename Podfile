# Uncomment this line to define a global platform for your project
source 'https://github.com/CocoaPods/Specs.git'
inhibit_all_warnings!

target 'ShadowsocksX-NG' do
  # Comment this line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for ShadowsocksX-NG
  pod 'Alamofire', '5.1.0'
  pod 'GCDWebServer'
  pod 'MASShortcut'

end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
#      config.build_settings['SWIFT_VERSION'] = '3.0'
    end
  end
end
