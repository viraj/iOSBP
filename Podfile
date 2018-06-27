# Uncomment the next line to define a global platform for your project
platform :ios, '11.0'

target 'iOSBP' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for iOSBP
    def testing_pods
        pod 'Quick'
        pod 'Nimble'
    end

    target 'Unit Tests' do
        testing_pods
    end

    target 'UI Tests' do
        testing_pods
        pod 'KIF'
    end

end
