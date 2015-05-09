# 安裝
```
sudo gem install cocoapods
```

# Podfile
```
platform :ios, '8.0'
use_frameworks!

target 'MyApp' do
  pod 'AFNetworking', '~> 2.5'
  pod 'ORStackView', '~> 2.0'
  pod 'SwiftyJSON', '~> 2.1'
end
```

```
pod install
```

#建立自己的POD
```
$ pod spec create Peanut
$ edit Peanut.podspec
$ pod spec lint Peanut.podspec
```

#參考
[CocoaPods提交初體驗](http://greenchiu.github.io/blog/2013/04/09/cocoapodsti-jiao-chu-ti-yan/)

