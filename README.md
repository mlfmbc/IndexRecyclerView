[![](https://jitpack.io/v/jiang111/IndexRecyclerView.svg)](https://jitpack.io/#jiang111/IndexRecyclerView)

###通过RecyclerView实现联系人的功能。

###usage:
Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:
```
	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```

Step 2. Add the dependency
```
	dependencies {
	        compile 'com.android.support:recyclerview-v7:23+'
	        compile 'com.github.jiang111:IndexRecyclerView:1.0'
	}
```

###demo:
1.首字母悬浮在顶部。<br />
2.侧滑删除联系人。<br />
3.联系人索引。<br />
<br />


效果图: <br />![效果](https://raw.githubusercontent.com/jiang111/IndexRecyclerView/master/art/art.gif)

<br />
<img src="https://raw.githubusercontent.com/jiang111/IndexRecyclerView/master/art/z.png" width="500" />

 <br />
  <br />
  <br />
 在head_recyclerview branch实现了带head的RecyclerView <br />
 
![效果](https://raw.githubusercontent.com/jiang111/IndexRecyclerView/master/art/head.gif)

###参考的第三方库(部分)：<br />
https://github.com/timehop/sticky-headers-recyclerview <br />
https://github.com/daimajia/AndroidSwipeLayout  

### License

    Copyright 2016 NewTab

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
