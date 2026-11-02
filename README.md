# 浙江足迹文献地图：网页发布包

这是已完成美化的网页，包含564条资料、21处地点与4部核心书目的目录。此发布包的首页与已交付的美化版逐字节一致。

## 文件说明

- index.html：唯一必需的网页文件，约5.08MB，已内嵌地图、字体、照片及目录数据。
- .nojekyll：供GitHub Pages识别的静态网站标记。
- README.md：本说明。

此文件夹仅包含网页成品，没有原站点的管理设置或仓库信息。

## 直接离线分享

将index.html发给同学，下载后用电脑浏览器打开。检索、地图、图片与字体无需联网；点击外部来源原文、图片来源链接时仍需网络。书签与笔记保存在每个人自己的浏览器中，不会自动同步给其他同学。

## GitHub Pages发布

1. 登录GitHub，用你自己有管理权限的账号新建公开仓库，例如zhejiang-footprints-atlas。GitHub Free支持公开仓库的Pages。
2. 解压发布包，在仓库中选择Add file → Upload files，把index.html和本说明放入仓库根目录并提交。不要直接上传ZIP作为网页，也不要把index.html再放进一层文件夹。
3. 打开仓库Settings → Pages。
4. Build and deployment中的Source选择Deploy from a branch。
5. Branch选择main，目录选择/(root)，点击Save。若你的默认分支名称不同，选择实际有index.html的分支。
6. 等GitHub显示发布成功后，使用Pages页面实际给出的地址。项目站点通常为“https://你的用户名.github.io/仓库名/”，这只是地址格式，不是已经开通的网址。
7. 请用校园网和手机流量分别测试能否打开。GitHub Pages官方没有保证中国大陆所有网络均可访问；切换平台后不能直接承诺免VPN。

GitHub官方说明：
https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 学校网页空间

请老师或学校信息中心确认：是否有支持静态HTML与JavaScript、允许公开或校外访问的网站空间。取得空间后，将index.html上传到指定首页目录即可。不能假定校园内部地址可供校外人员使用。此网页没有需要搭建的后端服务。

## 国内云托管

可用阿里云OSS或腾讯云COS托管，但当前新建实例的默认存储域名通常不能作为可直接预览HTML的正式分享地址，需要按平台要求绑定自定义域名。中国内地托管还应按平台指引满足备案要求；账号、域名、计费方式需要由所有者选择并完成。此包中的index.html可直接用作静态首页，不必重做网页。

阿里云官方：
https://help.aliyun.com/zh/oss/user-guide/hosting-static-websites
腾讯云官方：
https://cloud.tencent.com/document/product/436/32670
https://cloud.tencent.com/document/product/436/36638

## 内容与许可

- 文献目录、整理摘要与来源链接保持原有内容，目录条目不等于全文转载。
- 照片署名、拍摄时间、来源与CC BY-SA 4.0许可入口保留在网页中。
- Noto中文字体的SIL Open Font License 1.1许可全文已内嵌在“图片与字体来源”中。
- 发布包不是文献、图片或字体的统一重新授权；各项资料仍按原来源和许可使用。

## 当前状态

这是可上传的发布包，打包本身不会自动创建GitHub或国内云网站。新分享链接以目标平台实际发布成功后返回的地址为准。原ChatGPT托管链接保持原状。

整理日期：2026-11-02
