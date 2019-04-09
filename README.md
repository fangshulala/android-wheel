# 新财经项目说明文档
## 项目结构
![图片标题](https://leanote.com/api/file/getImage?fileId=5cac6fbcab6441156f002afb)

- assets
```javava
 assets中是百度语音相关的文件和查看pdf文件加载相关的
```
- api
```javava
1. request请求实体类相关
2. response回参实体类相关
3. IdeaApiService接口定义，retrofit方式
```
- base
```javava
1. BaseApplication程序入口，初始化相册配置、三方以及工具类等
2. DefaultExceptionHandler全局异常捕获类，出现异常后重启应用
3. BaseEvent，发送EventBus需要的实体类
```
- bean
```javava
实体类 另外一个同事开发加入的
```
- inter
```javava
接口包
```
- mvp
```javava
1.callback 回调接口
2.model 处理实际数据业务逻辑
3.presenter 中间层
4.view 接口回调
```
- net
```java
网络相关，包括拦截器，实体类转换等
```
- okhttp
```javava
okhttp封装相关
```
- recycler
```javava
和recyclerview相关
```
- third
```javava
三方封装的一些类，如百度语音播放等
```
- widget
```javava
自定义view
```
- wxapi
```javava
WXEntryActivity 微信分享
```
- utils
```javava 
工具类
```

- ui
```javava 
1.activity
2.adapter
3.fragment 
4.base Activity和framgment基类的封装
```
![图片标题](https://leanote.com/api/file/getImage?fileId=5caca1dbab64411769003354)

## 重要类说明
### capital包
* CapitalActivity 资本库列表
* CapitalDetailActivity 资本库详情
* SearchCapitalActivity 搜索资本库
### index包
* ArticleDetailActivity 资讯详情
* NewsListActivity 资讯列表
* SearchActivity 搜索页
* SearchArticleActivity 搜索资讯文章
* SearchResultActivity 搜索结果
### kuaixun包
* NewsFlashDetailActivity 快讯详情页
* PlayNewsFlashActivity 快讯播放页
* SearchFlashActivity 搜索快讯页
* ShareActivity 分享快讯页
### markitcap包
* AddOptionalActivity 添加自选页
* MarkitcapAppliesActivity 涨跌榜
* MarkitcapDetailActivity 行情详情
* MarkitCapWebViewActivity 行情webview展示页
* OptionalActivity 行情编辑页
* SearchMarkitcapActivity 搜索行情
### media包
* MediaActivity 媒体库列表
* MediaSinaDetailActivity媒体库微博详情
* MediaWeiXinDetailActivity 媒体库微信详情
* SearchMediaActivity 搜索媒体库
### project包
* ProjectActivity 项目库主页
* ProjectAddCommentActivity 添加项目库点评
* ProjectCommentActivity 个人项目评论
* ProjectDetailActivity 项目库详情主页
* ProjectReplayActivity 项目回复列表
* ReplayInputActivity 项目库点评回复
* SearchProjectActivity 搜索项目
* SeePdfActivity 查看白皮书 加载pdf
### user包
* AboutUsActivity 关于我们
* AddWalletActivity 添加钱包地址
* Articalavity 我的文章
* ArticleReviewsActivity 文章评论
* BindActivity 绑定邮箱或者手机号
* CandyActivity 我的糖果
* CandyRecordActivity 糖果记录
* ChangePassWordActivity 修改密码
* ChangePwdTwoActivity 修改密码确认
* CollectionActivity 我的收藏
* CommentDetailActivity 评论详情
* ConcernActivity 我的关注
* FeedBackActivity 意见反馈
* ForgetActivity 忘记密码
* GroupActivity 加入官方电报群
* HelperActivity 帮助与反馈
* ImageShowActivity 预览头像大图
* InputSoftFinshActivityTwo 软件盘弹出页面
* InvitationActivity 邀请好友
* LoginActivity 登录页面
* MessageActivity 系统消息
* ModifyActivity 修改手机或者邮箱
* ModifyNickNameActivity 修改昵称
* NoticeActivity 系统通知
* NoticeDetailActivity 系统通知详情
* ProfileActivity 个人简介
* RegisterActivity 注册页
* ReplayArticleInputActivity 文章评论回复
* ResetPwdActivity 重新设置密码
* RewardActivity 奖励页
* SettingActivity 设置页
* SignActivity 每日签到
* SignDialogActivity 签到弹窗
* UnBindMobileActivity 解绑手机
* UserInfoActivity 个人信息

#基础框架
##异步：RxJava+Retrofit

>[RxJava 与 Retrofit 结合的最佳实践](http://gank.io/post/56e80c2c677659311bed9841)

>[深入浅出RxJava（一：基础篇）](http://blog.csdn.net/lzyzsd/article/details/41833541)
[深入浅出RxJava(二：操作符)](http://blog.csdn.net/lzyzsd/article/details/44094895)
[深入浅出RxJava（三--响应式的好处）](http://blog.csdn.net/lzyzsd/article/details/44891933)
[深入浅出RxJava（四-在Android中使用响应式编程）](http://blog.csdn.net/lzyzsd/article/details/45033611)

>[快速Android开发系列网络篇之Retrofit](http://www.cnblogs.com/angeldevil/p/3757335.html)
[给 Android 开发者的 RxJava 详解](http://gank.io/post/560e15be2dca930e00da1083)
