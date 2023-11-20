project 'SignalR.Client.ObjC/SignalR.Client.ObjC.pbxproj'
workspace 'SignalR.Client.ObjC.xcworkspace'

target "SignalR.Client.iOS" do
    use_frameworks!
    platform :ios, '11.0'

    pod 'AFNetworking', '2.6.3'
    pod 'SocketRocket', '0.7.0'
    
    target "SignalR.Client.iOSTests" do
        pod 'OCMock'
    end
end

target :"SignalR.Client.OSX" do
    use_frameworks!
    platform :osx, '10.13'
    
    pod 'AFNetworking', '2.6.3'
    pod 'SocketRocket', '0.7.0'

    target :"SignalR.Client.OSXTests" do
        pod 'OCMock'
    end
end
