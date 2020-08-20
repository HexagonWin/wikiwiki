! [Alt text] (http://wiki.archve.ga/n1ghtshade/n1ghtshade.png)

[@synackuk](https://twitter.com/synackuk) 이 개발하는 iOS 다운그레이드 프로그램이다.
A6/A6x 탑재 기기들을 지원하며, 아이폰 5, 아이폰 5c, 아이패드 4 등의 기기들이 포함된다.
다운로드는 [여기](https://github.com/synackuk/n1ghtshade/) 에서 할수 있으며, [ipsw.me](http://ipsw.me/) 에서 기기용 ipsw 파일을 다운로드 받아 사용 가능하다.
[axi0mX](https://github.com/axi0mX) 가 발견한 하드웨어적 취약점인 [checkm8](https://www.theiphonewiki.com/wiki/Checkm8_Exploit) 취약점을 이용한다.
그래서 다운그래이드가 언테더(untethered, 재부팅 하여도 PC 없이 부팅 가능)가 아닌 테더(tethered, 재부팅시 PC에 연결하여 부팅해야함) 이다.
RC 버전들을 기준으로 정말 안정적이며, iOS 6.0 ~ iOS 9.3.5 까지의 다운그레이드를 지원한다고 한다.
하지만, iPhone 5 기준 다운그레이드 및 탈옥후 Cydia Substrate/Mobile Substrate 사용 트윅을 설치하면 사파리, 메일 등 여러 기본앱 및 서드파티 앱들이 동작하지 않게 되는 문제가 있다.
iOS 6.x에서는 [repo.mtmdev.org](repo.mtmdev.org) 레포지토리를 추가하고 Cydia Substrate 0.9.7100 을 내려받으면 해결되지만, 다른 버전은 되지 않는것으로 보인다.
만약 0.9.7100 설치후 부팅이 되지 않는다면 No Substrate Mode (부팅시 볼륨 위 계속 누르기) 로 들어가서 Cydia Substrate 를 다시 0.9.6*** 버전으로 내리고 일반모드 부팅후 Cydia를 사용하여 또다시 버전을 업그레이드 하면 된다. __단, 리스프링만 해야하며 재부팅 하면 고대로 다시 다 해야된다.__