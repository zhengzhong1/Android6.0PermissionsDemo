# Android6.0PermissionsDemo
Android拍照、相册访问图片剪裁适配到Android7.0，Android7.0中尝试传递 file:// URI 会触发 FileUriExposedException，因为在Android7.0之后Google认为直接使用本地的根目录即file:// URI是不安全的操作，直接访问会抛出FileUriExposedExCeption异常，这就意味着在Android7.0以前我们访问相机拍照存储时，如果使用URI的方式直接存储剪裁图片就会造成这个异常.
* 调用系统相机拍照

![image](https://github.com/zhengzhong1/Android6.0PermissionsDemo/blob/master/app/src/main/assets/GIF.gif)

* 打开系统相册

![image](https://github.com/zhengzhong1/Android6.0PermissionsDemo/blob/master/app/src/main/assets/GIF2.gif)
