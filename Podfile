platform :ios, "10.0"

use_frameworks! :linkage => :static

target "Target_Example" do
  pod "Target", :path => "../"
end

post_install do |installer|
  installer.pods_project.root_object.attributes["ORGANIZATIONNAME"] = "nuomi1"
end
