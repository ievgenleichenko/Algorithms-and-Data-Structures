platform :ios, '12.0'

#Common
use_frameworks!
pod 'SwiftLint'

# Application
target 'AlgorithmsAndDataStructures' do
    
end
 
# Tests or extension or...
target 'AlgorithmsAndDataStructuresTests' do
end

# Set 'Build active architecture only' to NO for all pods
post_install do |installer_representation|
  installer_representation.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['ONLY_ACTIVE_ARCH'] = 'NO'
    end
  end
end