---
description: >-
  앱 제공자가 사용자로 부터 필요한 리소스에 접근할 수 있는 권한을 설정하여 쿨에스엠에스 API 접근에 필요한 액세스 토큰 생성시, 필요한
  접근 권한을 사용자로 하여금 확인 후, 적절히 권한을 허가 할 수 있도록 합니다.
---

# 앱 권한 설정하기\(Scopes\)

### 요청된 권한과 허가된 권한에 대한 에러처리

앱 제공자가 요청한 권한에 대해서 사용자가 허가 않았을 경우에 이에 대한 에러 처리를 해주셔야 됩니다.  
예를 들어 앱 제공자가 user:basicProfile 권한을 요청했지만 사용자가 이를 거부한 경우,  
해당 사이트 또는 프로그램에서 이에 대한 에러 핸들링을 해주셔야 문제없이 서비스가 가능합니다.

### 사용가능한 권한 목록

**user**

* user:\*
* user:basicProfile
* user:cash
* user:

#### sms

* sms:\*
* sms:send
* sms:sent

#### senderId

* senderId:\*
* senderId:default
* senderId:list

#### admin

* admin:\*
* admin:createApiKey
* admin:readApiKey

{% hint style="warning" %}
위의 권한을 일단 임시로 등록
{% endhint %}







