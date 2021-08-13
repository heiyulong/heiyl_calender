# calendarview

日历控件


### 使用说明

**组件使用**

```
//工程的build.gradle添加如下配置
allprojects {
    repositories {
        ...
        jcenter()
        maven { url 'https://github.com/heiyulong/mavenlib/raw/master/' }
    }
    configurations.all {
        resolutionStrategy.cacheDynamicVersionsFor 10, 'minutes' // 动态版本
        resolutionStrategy.cacheChangingModulesFor 10, 'seconds' // 变化模块
    }
}
//引入依赖：
api 'com.heiyl.lib:lib_calender:1.0.0'
