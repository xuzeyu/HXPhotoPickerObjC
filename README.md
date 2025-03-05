
# HXPhotoPickerObjC

## 介绍
基于HXPhotoPickerObjC分支，继承原有功能，在原有功能上优化，主要是为了老版oc版本继续使用

## 如何导入
```
pod 'HXPhotoPickerObjC', :git => 'https://github.com/xuzeyu/HXPhotoPickerObjC.git'
```

## 修改
1、新增隐私协议PrivacyInfo.xcprivacy
2、增加参数以下参数
```objc
/// Cell的边框颜色
@property (nonatomic, strong) UIColor *borderColor;
/// Cell的边框圆角
@property (nonatomic, assign) CGFloat cornerRadius;
/// Cell的边框宽度
@property (nonatomic, assign) CGFloat borderWidth;
/// Cell的masksToBounds
@property (nonatomic, assign) BOOL masksToBounds;
/// 按钮的大小
@property (nonatomic, assign) CGSize itemSize;
/// 添加按钮图片的大小
@property (nonatomic, assign) CGSize addImageSize;
/// 只能拍摄video
@property (nonatomic, assign) BOOL onlyCamera;
```
