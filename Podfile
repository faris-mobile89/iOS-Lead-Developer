# Uncomment the next line to define a global platform for your project
 platform :ios, '11.0'

workspace 'iOS-Lead-Developer.xcworkspace'
project 'iOS-Lead-Developer.xcodeproj'

def networking_pod
  pod 'DependencyInjection', :path => 'DevPods/DependencyInjection'
end

def development_pods
  networking_pod
  #authentication_pod
  #movies_search_pod
end


target 'iOS-Lead-Developer' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  development_pods
  # Pods for iOS-Lead-Developer

end
