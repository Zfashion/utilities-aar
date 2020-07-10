# utilities-aar
# utilities的maven仓库
# 目前该库版本为1.0.1

# 引用方式：
1.第一步，先在项目的gradle文件添加url

allprojects {
    repositories {
       maven {
            url 'https://raw.githubusercontent.com/Zfashion/utilities-aar/master'
        }
    }
}

2.第二步，在module的gradle文件中添加依赖

implementation 'com.zSupportFLibrarys:UtilitiesLib:1.0.1'