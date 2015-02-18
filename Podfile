source 'https://github.com/CocoaPods/Specs.git'

platform :ios, '8.0'

# Allows per-dev overrides
local_podfile = "Podfile.local"
eval(File.open(local_podfile).read) if File.exist? local_podfile

target 'BaseProject' do
    pod 'AFNetworking', '~> 2.0'
    pod 'Typhoon', '2.3.4'
    pod 'FontAwesomeKit/FontAwesome', '2.1.8'
    pod 'FontAwesomeKit/IonIcons', '2.1.8'
    pod 'ORStackView', '2.0.0'
    pod 'XYPieChart', :git => 'https://github.com/danydev/XYPieChart.git'
    pod 'DWTagList', :git => 'https://github.com/danydev/DWTagList.git'
    pod 'MGSwipeTableCell', '1.3.4'
    pod 'IQKeyboardManager', '3.2.0.3'
    pod 'PNChart', '0.6.0'
    pod 'JVFloatLabeledTextField', '1.0.0'
    pod 'SDWebImage', '3.7.1'
    pod 'FMDB', '2.5'
end
