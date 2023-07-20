使用教程（文档）：<a href="https://afubaba.github.io/Afreecatv/libs/pdf/%E6%89%A9%E5%B1%95%E4%BD%BF%E7%94%A8%E6%89%8B%E5%86%8C.pdf" target="_blank" rel="nofollow">扩展使用手册(chinese)</a>
--
使用教程（视频）:<a href="https://afubaba.github.io/Afreecatv/" target="_blank" rel="nofollow">本扩展使用教程</a>
--
#下面的同版本的脱机版和在线版的插件功能和界面几乎没有差异，只有静态资源存储位置不同，适用于以Chrome为核心的游览器
--
mv3支持的浏览器：Microsoft Edge、Naver-whale、Google-Chrome、Opera等以Chrome为核心浏览器或支持 manifest v3的其他浏览器
--
脱机版本发布后将在一段时间内更新在线版本。
--
V3.1.5-mv3-websql&indexdb在线版本：v3.1.4-mv3-websql&indexdb的升级版本，此版本将Manifest MV3用作可访问github网络环境的计算机的插件，插件所需资源由github托管。
--
V3.2.5-MV3-Websql&IndexDB&Mysql脱机版：v3.2.4-mv3-websql&indexdb的升级版，此版本使用Manifest MV3作为插件访问本地静态资源，不访问网络上的资源。插件所需的资源已集成到插件文件夹中。
--
1.此版本中新增了远程数据库Mysql，需要构建本地远程服务器环境才能使用。

2.此版本解决了某些机器人命令的问题。界面详细优化。

v3.1.4-mv3-websql&indexdb在线版：3.1.1-mv3的升级版，此版本适用于可访问github网络环境的电脑，插件所需的资源由github托管
--
v3.2.4-mv3-websql&indexdb脱机版：3.2.1-mv3的升级版，下载时请附带下载视频背景文件background.mp4，如果您不喜欢这个视频，可以换成其他视频并将其重命名为background.mp4，放到3.2.4-mv3/video/background.mp4文件夹中（v3.2.4/v3.2.5等新版本的脱机版 若使用视频背景都需要下载background.mp4）。
--
1.从主页双击空白处 则播放视频背景并隐藏主页内容，再次双击即可显示主页内容，进入直播间开启聊天运动模式也可以开启静音版的视频背景

2.本地时间改为 互联网时间。如果浏览器是韩文，则读取的是韩国时间，如切换到中文页面，会自动将+1小时变为韩国时间。

3.新增LOL游戏角色选择功能，使用LOL命令 随机选出一个角色推荐给主播。

4.添加聊天统计功能（聊天统计点开关，龙王通知，查看统计点）。第一名获得龙王图标。随着聊天点的增加，图标按聊天点/75的比率、最大增加到60px*60px（v3.1.5/v3.2.5则没有尺寸上限），不再增加。新增两个机器人命令(!ace!용왕（龙王的意思）)实时查询，该版本的聊天点统计 目前只存储在使用插件的浏览器上，不同的浏览器数据互不相通

5.添加了发送内容 输入框储存历史发送记录的功能，输入部分内容即可提示补全消息。页面刷新时会失去发送的内容记录。脚本附带的机器命令的提示则永远不会清除

6.权限管理：权限必须受到限制，支持自定义授权机器人命令使用者的权限，以允许特定用户使用机器人命令，包括登录的用户、BJ、订阅者和狂热粉丝等自定义。

7.聊天点游戏支持从本游览器手动导入到其他游览器，在切换聊天点统计数据库时自动合并数据。

8.大量机器人命令已知BUG，修改界面美化

版本特性：兼容所有之前的离线版本的机器人命令，如上一版本，该版本优化了机器命令的对比方式，修复了一些错误，优化了界面部分，在聊天室冻结模式下读取信息，优化了内容读取，优化了屏幕效果，提高了性能优化，由于阅读信息部分的核心框架发生了重大变化，因此它将更新为新版本，并继续支持旧版本。该版本不再读取无用的图片表情符号。
--
3.1.1-mv3/3.1.1-mv3-emoji在线版本：v1.2-mv2的升级版本，此版本适用于可访问github网络的环境的电脑，插件所需的资源由github托管
--
3.2.1-mv3/3.2.1-mv3-emoji脱机版：v2.2-mv2的升级版本，此版本不访问网络上的资源。独立。插件所需的资源已整合到插件文件夹中。
--
版本特点：支持以前版本的所有功能，增加了机器人聊天随机选择LOL英雄名字的功能，这个版本对阅读图片表情效果很好，这个版本只注重mv2->mv3的升级阶段。
如果您的计算机不支持谷歌表情，请使用3.1.1-mv3-emoji/3.2.1-mv3-emoji表情增强版，此版本使用图片代替表情，以支持不显示谷歌表情的浏览器。因此，启动时可能会占用更多的系统资源。
--

Manifest version 2 is deprecated, and support will be removed in 2023. See https://developer.chrome.com/blog/mv2-transition/ for more details.

翻译：清单2被废弃，可能会在2023年删除，如图所示https://developer.chrome.com/blog/mv2-transition/更多的细节。

根据谷歌官方公告，截至2023年，目前低版本manifest v2.0兼容大多数游览器，如果你使用Chrome以外的浏览器，请使用这两个版本
--
v1.2-mv2在线版本（mv2版本支持大多数浏览器）：此版本使用Manifest mv2作为插件访问github资源（https://github.com/afubaba/Afreecatv）用于网络速度更快的客户端，此版本适用于可以访问github网络环境的电脑，插件所需的资源托管在github上
--
v2.2-mv2脱机版（mv2版本支持大多数浏览器）：此版本使用Manifest mv2作为插件访问本地静态资源，不访问网络上的资源。独立。插件所需的资源已集成到插件文件夹中。
--
功能：内置弹幕提示，字体优化，设备显示，聊天机器人（测试中）<a href='https://afubaba.github.io/Afreecatv/RobotCommand.html' target='_blank'>命令手册</a>  管理员刷屏功能，支持打开连接到Instagram的所有相册，
--
注意：如果使用批量发送或聊天机器人，请确保权限帐户具有多次发送内容的权限。此扩展不绕过官方限制，只模拟手动输入。
--
隐藏：清晰度调整显示
--
恢复：阻止bj.afreecatv.com部分无法加载的js，转到可用地址
--
该插件将自动永久保留特殊效果之外的特殊效果，下次启动游乐器时无需重新输入控制器。安装插件后直接访问主站点https://afreecatv.com，自动访问效果，无需进行其他操作
--
[//]: # ([本扩展使用教程/이 확장 사용 강좌]&#40;<https://afubaba.github.io/Afreecatv/>{:target="_blank"}&#41;)

[//]: # ([]&#40;<http://yinping4256.github.io>{:target="_blank"}&#41;)

[//]: # ([example]&#40;http://yinping4256.github.io&#41;{:target="_blank"})

[//]: # (<http://yinping4256.github.io>{:target="_blank"})
자습서 사용하기 (문서):  <a href="https://afubaba.github.io/Afreecatv/libs/pdf/%ED%99%95%EC%9E%A5%20%EC%82%AC%EC%9A%A9%20%EC%84%A4%EB%AA%85%EC%84%9C.pdf" target="_blank" rel="nofollow">확장 사용 설명서(korean)</a>
--
자습서 사용하기 (영상)：<a href="https://afubaba.github.io/Afreecatv/" target="_blank" rel="nofollow">이 확장 사용 강좌</a>
--
# 아래 같은 버전의 오프라인 버전과 온라인 버전의 플러그인 기능과 인터페이스는 거의 차이가 없다. 정적 자원 저장 위치만 다르다. 크롬을 핵심으로 하는 유람기에 적합하다
--
mv3 지원 브라우저: Microsoft Edge, Naver-whale, Google-Chrome, Opera 등 크롬을 중심으로 하거나 manifest v3를 지원하는 기타 브라우저
--
V3.1.5-mv3-websql&indexdb온라인 버전:v3.1.4-mv3-websql&indexdb의 업그레이드 버전，이 버전은 Manifest MV3를 github 네트워크 환경에 액세스할 수 있는 컴퓨터에 플러그인으로 사용하며, 플러그인에 필요한 리소스는 github에서 호스팅됩니다.
--
V3.2.5-MV3-Websql&IndexDB&Mysql오프라인판:v3.2.4-mv3-websql&indexdb의 업그레이드 버전，이 버전은 Manifest MV3를 플러그인으로 사용하여 로컬 정적 리소스에 액세스하며 네트워크의 리소스에는 액세스하지 않습니다.독립하다.플러그인에 필요한 자원이 플러그인 폴더에 통합되었습니다.
--
1.이 릴리즈에는 원격 데이터베이스 Mysql이 새로 추가되어 로컬 원격 서버 환경을 구축해야 사용할 수 있습니다.
2.이 버전은 일부 로봇 명령의 문제를 해결합니다.인터페이스 세부 최적화.

v3.1.4-mv3-websql&indexdb온라인 버전:3.1.1-mv3의 업그레이드 버전，이 버전은github 네트워크 환경에 접근할 수 있는 컴퓨터에 적용된다,플러그인에 필요한 자원은github에 위탁 관리됩니다
--
v3.2.4-mv3-websql&indexdb 오프라인 버전: 3.2.1-mv3 업그레이드 버전, 다운로드 시 비디오 배경 파일 background.mp4 다운로드 첨부 이 비디오가 마음에 들지 않으면 다른 비디오로 바꾸고 background.mp4 로 이름을 바꾸어 3.2.4-mv3/video/background.mp4 폴더에 넣을 수 있습니다.(v3.2.4/v3.2.5 등 새로운 버전의 오프라인 버전은 비디오 배경을 사용하려면 background.mp4를 다운로드해야 함) 
--
1. 홈 페이지 더블 클릭 공백에서 비디오 배경으로 전환，생방송에 들어가는 운동 모드 설정을 배경 영상으로 업데이트합니다

2.현지 시간을 인터넷 시간으로 변경합니다.브라우저가 한국어인 경우 한국시간을 읽고, 중국어 페이지로 전환하면 자동으로 + 1시간이 한국시간으로 바뀝니다.

3.새로운 LOL 게임 캐릭터 선택 기능을 추가합니다.LOL 명령을 사용하여 랜덤으로 캐릭터 하나를 선택하여 앵커에게 추천합니다.

4. 채팅 통계 기능 추가(채팅 통계점 스위치, 용왕 알림, 통계점 보기).1등은 용왕 아이콘을 획득.채팅 지점이 증가함에 따라 아이콘은 채팅 지점/75의 비율에 따라 최대 60px * 60px (v3.1.5/v3.2.5는 사이즈 상한이 없음) 로 증가하여 더 이상 증가하지 않는다.두 개의 로봇 명령 (!ace!용왕) 실시간 조회가 추가되었습니다. 이 버전의 채팅점 통계는 현재 플러그인을 사용하는 브라우저에만 저장되어 있습니다. 서로 다른 브라우저 데이터는 서로 통하지 않습니다.

5. 발송 내용 입력란에 과거 발송 기록을 저장하는 기능을 추가하여 일부 내용을 입력하면 보충 메시지를 알릴 수 있습니다.페이지를 새로 고치면 전송된 컨텐츠 레코드가 손실됩니다.스크립트에 포함된 기계 명령의 프롬프트는 영원히 지워지지 않습니다

6. 권한 관리: 권한은 제한되어야 한다. 사용자 정의 권한 수여 로봇 명령 사용자의 권한을 지원하여 특정 사용자가 로봇 명령을 사용할 수 있도록 허용한다. 로그인한 사용자, BJ, 구독자, 광팬 등 사용자 정의를 포함한다.

7. 채팅 포인트 게임은 본 유람기에서 다른 유람기로 수동으로 가져오고 채팅 포인트 통계 데이터베이스를 전환할 때 자동으로 데이터를 병합할 수 있습니다.

8. 대량의 로봇 명령 알려진 BUG, 인터페이스 미화 수정

버전 특성：이전 버전과 같은 버전의 오프라인 버전의 모든 로봇 명령 호환 이 버전은 기계 명령의 비교 방식을 최적화하고 일부 버그를 복구하며 인터페이스 부분을 최적화한다，채팅방 동결 모드에서 정보 읽기, 내용 읽기 최적화, 화면 효과 최적화, 성능 최적화 증가,읽기 정보 부분의 핵심 프레임워크가 크게 바뀌었기 때문에 새 버전으로 업데이트되고 이전 버전을 계속 지원합니다.이 버전은 더 이상 쓸모없는 그림 이모티콘을 읽지 않습니다
--
[//]: # (호환성：ubuntu/lubuntu 18.4amdx64&#40;linux&#41; 버전 이하, 크롬 핵심 여러 개의 유람기의 102/103 최신 버전은 웹sql에 빈번한 CRUD로 인해 한동안 생방송이 끊기고 가짜 네트워크가 끊기고 검은 화면 등 문제가 발생할 수 있습니다. 이 문제는 공식적으로 해결해야 합니다.문제가 발생하면 indexdb 데이터베이스로 전환)

[//]: # (윈도우즈의 유람기는 웹 sql를 사용할 수 있고 indexdb를 사용할 수 있으며 버전의 영향을 받지 않습니다)

3.1.1-mv3/3.1.1-mv3-emoji온라인 버전:v1.2-mv2의 업그레이드 버전，이 버전은github 네트워크 환경에 접근할 수 있는 컴퓨터에 적용된다,플러그인에 필요한 자원은github에 위탁 관리됩니다
--
3.2.1-mv3/3.2.1-mv3-emoji오프라인판:v2.2-mv2의 업그레이드 버전，이 버전은 네트워크의 자원에 접근하지 않습니다. 독립 실행형입니다.플러그인에 필요한 자원이 플러그인 폴더에 통합되었습니다.
--
버전 특성：이전 버전의 모든 기능 지원，로봇 채팅 랜덤으로 LOL 영웅 이름 선택 기능 추가,이 버전은 그림 표정 읽기에 효과가 좋다，이 버전은 mv2->mv3의 업그레이드 단계에만 중점을 둡니다.

컴퓨터에서 Google 이모티콘을 지원하지 않는 경우 3.1.1-mv3-emoji/3.2.1-mv3-emoji 이모티콘 향상 버전을 사용하십시오. 이 버전은 이모티콘 대신 이미지를 사용하여 Google 이모티콘을 표시하지 않는 브라우저를 지원합니다.따라서 부팅 시 시스템 자원이 더 많이 사용될 수 있습니다.
--

Manifest version 2 is deprecated, and support will be removed in 2023. See https://developer.chrome.com/blog/mv2-transition/ for more details.
번역: 목록 2가 폐기되어 2023년에 삭제될 수 있습니다. 그림과 같습니다.https://developer.chrome.com/blog/mv2-transition/더 많은 디테일.

구글 공식 발표에 따르면 2023년까지 현재 저버전 manifest v2.0은 대부분의 유람기와 호환되며 크롬 이외의 브라우저를 사용할 경우 이 두 버전을 사용하십시오.
--
v1.2-mv2 온라인 버전(mv2 버전은 대부분의 브라우저를 지원): 이 버전은 Manifest mv2를 플러그인으로 사용하여 github 리소스에 액세스합니다(https://github.com/afubaba/Afreecatv) 네트워크 속도가 더 빠른 클라이언트를 위한 이 버전은 github 네트워크 환경에 액세스할 수 있는 컴퓨터에 적용되며, 플러그인에 필요한 자원은 github에 호스팅됩니다.
--
v2.2-mv2 오프라인(mv2 버전은 대부분의 브라우저를 지원): 이 버전은 Manifest mv2를 플러그인으로 사용하여 로컬 정적 리소스에 액세스하며 네트워크의 리소스는 액세스하지 않습니다.독립하다.플러그인에 필요한 자원이 플러그인 폴더에 통합되었습니다.
--
기능：내장 탄모 힌트, 글씨체 최적화, 설비 디스플레이, 채팅 로봇（테스트 중）<a href="https://afubaba.github.io/Afreecatv/RobotCommand.html" target="_blank">명령 매뉴얼</a>, 관리자 도배 기능，인스타그램에 연결된 모든 앨범 열기 지원,
--
주의사항：대량 발송이나 채팅 로봇을 사용하면 권한 계정이 여러 번 내용을 발송할 수 있는 권한을 가지고 있는지 확인하십시오. 본 확장은 공식적인 제한을 빙빙 돌려서 하는 것이 아니라 수동 입력만 시뮬레이션합니다.
--
숨김 기능: 선명도 조정 디스플레이
--
복구: 차단 bj.afreecatv.com 부분 불러올 수 없는 js, 사용 가능한 주소로 이동
--
이 플러그인은 특수효과 외부의 특수효과를 자동으로 영구적으로 보존하고 다음에 유람기를 시작하면 다시 컨트롤러에 입력할 필요가 없습니다. 플러그인 설치 후 운영 사이트에 직접 액세스https://afreecatv.com, 추가 작업 없이 효과를 자동으로 액세스
--

