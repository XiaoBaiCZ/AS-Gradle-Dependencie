# AS-Gradle-Dependencie
安卓Gradle常用依赖字符串

# AndroidX
~~~
implementation 'androidx.appcompat:appcompat:+'
~~~

# KTX
~~~
implementation 'androidx.core:core-ktx:+'
~~~

# MaterialDesign
~~~
implementation 'com.google.android.material:material:+'
~~~

# Jetpack
~~~
//lifecycle
implementation 'androidx.lifecycle:lifecycle-runtime:+'
//livedata
implementation 'androidx.lifecycle:lifecycle-livedata:+'
//viewmode
implementation 'androidx.lifecycle:lifecycle-viewmodel:+'

//viewmode + livedata + lifecycle
implementation 'androidx.lifecycle:lifecycle-extensions:+'

//navigation
implementation 'androidx.navigation:navigation-fragment-ktx:+'
implementation 'androidx.navigation:navigation-ui-ktx:+'

//room
implementation 'androidx.room:room-runtime:+'
//kapt
implementation 'androidx.room:room-compiler:+'
//coroutine support
implementation 'androidx.room:room-ktx:+'

//work
implementation 'androidx.work:work-runtime:+'
//coroutine
implementation 'androidx.work:work-runtime-ktx:+'
~~~

# Coroutine
~~~
implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-core:+'
implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-android:+'
~~~

# ConstraintLayout
~~~
implementation 'androidx.constraintlayout:constraintlayout:+'
~~~

# Gson
~~~
implementation 'com.google.code.gson:gson:+'
~~~

# okhttp
~~~
implementation 'com.squareup.okhttp3:okhttp:+'
~~~

# Retroft
~~~
implementation 'com.squareup.retrofit2:retrofit:+'
//gson
implementation 'com.squareup.retrofit2:converter-gson:+'
//jackson
implementation 'com.squareup.retrofit2:converter-jackson:+'
//moshi
implementation 'com.squareup.retrofit2:converter-moshi:+'
//protobuf
implementation 'com.squareup.retrofit2:converter-protobuf:+'
//wire
implementation 'com.squareup.retrofit2:converter-wire:+'
//simplexml
implementation 'com.squareup.retrofit2:converter-simplexml:+'
//scalars
implementation 'com.squareup.retrofit2:converter-scalars:+'
~~~

# Glide
~~~
implementation 'com.github.bumptech.glide:glide:+'
//annotationProcessor
implementation 'com.github.bumptech.glide:compiler:+'
~~~

# 我的工具
~~~
//地址
maven { url 'https://jitpack.io' }
//权限
implementation 'com.github.XiaoBaiCZ:Permissions:v0.1'
//列表扩展
implementation 'com.github.XiaoBaiCZ:RecyclerViewExtend:v0.3'
//小工具
implementation 'com.github.XiaoBaiCZ:Helper:v0.3.2'
