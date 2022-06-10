# 说明
增加了64位支持的https://github.com/bilibili/NativeBitmapFactory 仅仅去掉了armv5（armeabi），变量类型`uint32_t`->`uint64_t`，加入64编译就可

参考资料 https://github.com/bilibili/NativeBitmapFactory/issues/1
# 使用方法
## A.作为Gradle项目使用

#### 1.克隆项目

`git clone https://gitee.com/hydrogenium2020/native-bitmap-factory NativeBitmapFactory`

#### 2.引入项目

在`settings.gradle`文件中加入

    include ':NativeBitmapFactory'

然后在`build.gradle`文件
`dependencies`函数下加入
    
    implementation project(':NativeBitmapFactory')

## B.编译so
### Linux
`cd src\main\jni` 

`NDK目录\ndk-build` 就可以了

## C.编译成aar
### 待探索

# License
本项目遵循Apache 2.0协议
Copyright (C) 2022 Hydrogenium2020

Copyright (C) 2013-2015 Chen Hui <calmer91@gmail.com>


Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.