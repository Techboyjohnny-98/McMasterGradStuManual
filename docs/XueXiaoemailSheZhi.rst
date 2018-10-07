﻿学校email激活与收发
===========================
.. attention::
   **学校email只有等注册后才能激活**

学校的邮件系统为所有学生和员工提供一个 MacID@mcmaster.ca 的邮箱，具体分为2部分

- 本科生和研究生使用的是Google的企业邮箱服务，就是Gmail的企业版，在国内无法登陆，甚至激活都不可以，大家来Canada之后再激活登陆。如果想在国内激活并访问，请自行搜索翻墙方法。
- Post doc、访问学者、联培学生和学校教职工使用的是Microsoft Exchange企业邮箱，就是outlook.com的企业版，这个在国内可以登陆，注册完之后就可以激活并且使用了。

激活方法
---------------------------------------
第一步：登陆mosaic之后，在右上角点击三个横线的图标，再点"NavBar"。

.. image:: /resource/XueXiaoemailSheZhi/activate_email_on_phone_1.png
   :align: center
   :scale: 50%

第二步：选择Navigator

.. image:: /resource/XueXiaoemailSheZhi/activate_email_on_phone_2.png
   :align: center
   :scale: 50%

第三步：选择Email Management

.. image:: /resource/XueXiaoemailSheZhi/activate_email_on_phone_3.png
   :align: center
   :scale: 50%

第四步：点击“Manage your Email Service”，找到学校的邮箱，选择Activate。同时也设置一下Primary Email Account，就是默认接受学校发的Email的邮箱。

.. image:: /resource/XueXiaoemailSheZhi/activate_email_on_phone_4.png
   :align: center
   :scale: 50%

| 以上截图感谢17-PH-朱莹提供
| 在激活的的时候显示的邮箱是@studentmail.os.mcmaster.ca，但实际在用的时候请把后缀写成@mcmaster.ca。https://www.mcmaster.ca/uts/selfservice/student_email.html

学校写的指导教程：http://www.mcmaster.ca/uts/macid/

在线登录方法
-----------------------------------------------
- 本科生、研究生：https://studentmail.mcmaster.ca
- Post doc、访问学者、联培学生和学校教职工：https://macmail.mcmaster.ca/

邮箱客户端收发方法
-------------------------------------------------
iOS和macOS自带的邮件客户端只能收邮件不能发邮件，请最好用Outlook或Gmail客户端。

1. 本科生、研究生

 | 首先在邮箱网页里设置允许IMAP协议和允许客户端访问（见附1）。然后是两种设置客户端的方法。

- 方法一：

 | Account type: IMAP 
 | Incoming server: mcmasterimap.mcmaster.ca 
 | Outgoing server: mcmastersmtp.mcmaster.ca 
 | SSL encryption for both incoming and outgoing servers turned on. 
 | Incoming port 993 
 | Outgoing port 465 
 | Outgoing server to require authentication using the same credentials as the incoming server. 
 | 具体看这里： https://www.mcmaster.ca/uts/selfservice/documents/Studentmail_Outlook_%202016.pdf

- 方法二（建议）

 | 使用客户端自动配置功能。见附2、附3。如果你已经把课程安排导入Google calendar，用这种方法还可以在同步邮箱的同时，同步Google calendar。这样就可以在客户端上看每周课程安排了。

2. Post doc、访问学者、联培学生和学校教职工

 | Outlook客户端：https://macmailhelp.mcmaster.ca/docs/default-source/default-document-library/how-to-configure-outlook2016.pdf?sfvrsn=2
 | iPhone： http://macmailhelp.mcmaster.ca/docs/default-source/default-document-library/uts-documents/macmail---how-to-configure-iphone.pdf?sfvrsn=2
 | Android: http://macmailhelp.mcmaster.ca/docs/default-source/default-document-library/uts-documents/macmail---how-to-configure-android.pdf?sfvrsn=2 
 | 更多：https://macmailhelp.mcmaster.ca/MacMail/help

如果有其它原因导致Email收发不成功，请联系学校UTS，http://www.mcmaster.ca/uts/

注
--------------------------------------
1) Android phones：May require that the encryption method be set SSL-accept all certificates instead of just SSL。
#) MACID区分大小写。
#) 学校的邮箱在没激活之前，都会先转发到你的申请邮箱里。学校Email激活后可以设置默认转发到McMaster的邮箱里，方法是mosaic->Student Center->Personal Information->email addresses，把你希望设置为默认接受学校邮件的Email勾上Preferred。
#) 邮箱激活后可能需要几天才能正常收发邮件。
#) 由于Gmail邮箱无法在国内访问，所以大家最好申请一个Outlook或Yahoo的邮箱作为以后个人长期使用的邮箱。

附
-------------------------------------------
1) 设置允许IMAP协议和允许客户端访问

| 第一步：在网页上登录邮箱选”Settings“。

.. image:: /resource/XueXiaoemailSheZhi/IMAP_1.png
   :align: center

| 第二步：在“Forwarding and POP/IMAP”列表下，选择“Enable IMAP”。然后点“Save Changes”。

.. image:: /resource/XueXiaoemailSheZhi/IMAP_2.png
   :align: center

| 第三步：点击右上角头像图标，在弹出框里选“My Account”。

.. image:: /resource/XueXiaoemailSheZhi/IMAP_3.png
   :align: center

| 第四步：点击“Apps with account access”。

.. image:: /resource/XueXiaoemailSheZhi/IMAP_4.png
   :align: center

| 第五步：把“Allow less secure apps”的开关打开。

.. image:: /resource/XueXiaoemailSheZhi/IMAP_5.png
   :align: center

2) 手机Outlook客户端设置方法（本科生、研究生的邮箱）

| 第一步：下载客户端
| iOS：https://itunes.apple.com/ca/app/microsoft-outlook-email-and-calendar/id951937596?mt=8
| Android：https://play.google.com/store/apps/details?id=com.microsoft.office.outlook

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_1.png
   :align: center
   :scale: 25%

| 第二步： 打开后点击左上角的三条横线的图标，然后点击加号。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_2.png
   :align: center
   :scale: 25%

| 第三步：输入McMaster邮箱的地址：MacID@mcmaster.ca。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_3.png
   :align: center
   :scale: 25%

| 第四步：点击右上角“Not Exchange”。再选“Change Account Provider”。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_4.png
   :align: center
   :scale: 25%

| 第五步：选“Google”。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_5.png
   :align: center
   :scale: 25%

| 第六步：在弹出的网页里登录邮箱。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_6.png
   :align: center
   :scale: 25%

| 第七步：点击McMaster的邮箱账户。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_7.png
   :align: center
   :scale: 25%

| 第八步：点击Allow。Outlook客户端就会开始自动同步McMaster邮箱。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_8.png
   :align: center
   :scale: 25%

| 最后，在outlook手机客户端就可以收发McMaster邮箱的邮件了。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_9.png
   :align: center
   :scale: 25%

| 如果已经把课程表导入到McMaster邮箱附带的Google calendar里，则日历也会同步。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_10.png
   :align: center
   :scale: 25%

3) 电脑Outlook客户端设置方法（本科生、研究生的邮箱）

 | 首先确保你的电脑上已经安装了Outlook客户端。如果没安装，请参考 `办公软件和网盘`_ 里安装office365的教程。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_icon.png
   :align: center
   :scale: 50%

| 第一步：打开Outlook客户端，它会自动提示新建账户，填写McMaster邮箱的地址 MacID@mcmaster.ca。点“Advanced options”，然后勾上“Let me set up my account manually”。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_01.png
   :align: center
   :scale: 40%

| 第二步：点击IMAP的图标。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_02.png
   :align: center
   :scale: 40%

| 第三步：输入McMaster邮箱的设置信息，这个在上面已经提到了。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_03.png
   :align: center
   :scale: 40%

| 第四步：输入mosaic的密码。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_04.png
   :align: center
   :scale: 40%

| 第五步：一个设置成功的页面，点击Done即可。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_05.png
   :align: center
   :scale: 40%

对于Windows系统，可以设置把Outlook后台运行。在桌面右下角的系统托盘里右键点击Outlook的图标，然后选择“Hide When Minimized”，这样点最小化后，Outlook就会后台运行，来新邮件之后会有提醒。也可以设置为开机自动启动（参考Windows 8的教程）：https://support.office.com/en-us/article/automatically-start-an-office-program-when-you-turn-on-your-computer-4a42ed45-c064-47b6-b497-119c870f7bab

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_settings_01.png
   :align: center
   :scale: 50%

由于学校的Email非常多，如果全部都同步到电脑里将占用很大一部分硬盘空间。我们可以把它设置成只同步最近一个月的邮件：

| 第一步：在Outlook窗口中点击“File”，这样就进入到了Info页面，点击“Account Settings...”。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_sync_01.png
   :align: center

| 第二步：选择McMaster的邮箱账户，点“Change”。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_sync_02.png
   :align: center

| 第三步：在弹出框里，把“Keep mail offline for”，设置成1 month。点next，后面Outlook会自动完成相应的设置。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_sync_03.png
   :align: center
   :scale: 40%

Outlook桌面客户端需要额外设置同步Google Calendar，以下是步骤：

| 第一步：打开Google Calendar：https://calendar.google.com/ 。使用McMaster的邮箱账户登录。
| 在左侧点击有课程表的日历的右边向下的箭头。点击“Calendar settings”。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_calendar_01.png
   :align: center

| 第二步：在“Private Address”那一栏里点击“ICAL”的图标。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_calendar_02.png
   :align: center

| 第三步：复制弹出框中的链接。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_calendar_03.png
   :align: center

| 第四步：打开Outlook桌面客户端，在左下角点击日历的图标。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_calendar_04.png
   :align: center
   :scale: 50%

| 第五步：右键点击左侧“Other Calendars”->“Add Calendar”->“From Internet...”

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_calendar_05.png
   :align: center
   :scale: 50%

| 第六步：在弹出框中粘贴之前网页里的链接。点“OK”。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_calendar_06.png
   :align: center
   :scale: 50%

| 第七步：在弹出框里选“Yes”。这样Outlook客户端就会按一定频率检查Google Calendar，如果有更新就会实时更新到Outlook客户端里。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_calendar_07.png
   :align: center
   :scale: 50%

| 然后就可以在Outlook里查看McMaster邮箱的Calendar了。

.. image:: /resource/XueXiaoemailSheZhi/outlook_desktop_calendar_08.png
   :align: center

.. _办公软件和网盘: BanGongRuanJianHeWangPan.html