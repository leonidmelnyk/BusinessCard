platform :ios, '10.0'

# define macro
def component(name)
	pod "ComponentsHub/#{name}", :git => 'https://github.com/leonidmelnyk/ios-hub.git', :branch => 'master'
end

target 'BusinessCard' do
  
  use_frameworks!
  
  component 'Table'
  component 'Macroses'
  component 'ManualLayout'
  
  
#  target 'BusinessCardTests' do
#    inherit! :search_paths
#    # Pods for testing
#  end
#
#  target 'BusinessCardUITests' do
#    inherit! :search_paths
#    # Pods for testing
#  end

end
