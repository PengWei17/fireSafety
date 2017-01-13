#移动应用管理

##介绍
>
项目App软件更新

###功能
>
+ 查询
+ 添加
+ 更新
+ 删除

###查询:
	传入参数：  
			platform    //运行平台  1：ios，2：android，3：package
			appid       //app的ID号
			version     //原版本号
	反馈：
		有新版本：
			isUpdate    //是否强制更新 0：无变化，1：可更新，2：强制更新
			desc        //更新内容
			updateTime  //更新时间，格式：2017-01-10
			downloadURL //更新下载地址，格式：www.baidu.com
			hash        //解密码
		无新版本：
			isUpdate    //返回0，版本无变化

###添加：
    传入参数：
            platform    //运行平台  1：ios，2：android，3：package
            appid       //appID号
            appname     //app名
            version     //新版本号，不能与以前版本号相同
            isUpdate    //是否强制更新0：无变化，1：可更新，2：强制更新
            desc        //更新内容
            updateTime  //更新时间，格式：2017-01-10
            downloadURL //更新下载地址，格式：www.baidu.com
			hash		//解密码

###更新：
    传入参数：
            platform    //运行平台  1：ios，2：android，3：package
            appid       //appID号
            appname     //app名
            version     //新版本号，不能与以前版本号相同
            isUpdate    //是否强制更新0：无变化，1：可更新，2：强制更新
            desc        //更新内容
            updateTime  //更新时间，格式：2017-01-10
            downloadURL //更新下载地址，格式：www.baidu.com

###删除：
    传入参数：
            id   //根据id进行删除

##说明
###实例暂无，待后续添加！




