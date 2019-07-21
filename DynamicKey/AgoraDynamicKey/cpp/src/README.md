- **RtcTokenBuilder.h**: Source code for generating a token for the following SDKs:
  - Agora Native SDK v2.1+
  - Agora Web SDK v2.4+
  - Agora Recording SDK v2.1+
- **RtmTokenBuilder.h**: Source code for generating a token for the Agora RTM SDK. 
- **AccessToken.h**: Implements all the underlying algorithms for generating a token. Both **RtcTokenBuilder.h** and **RtmTokenBuilder.h** are a wrapper of **AccessToken.h** and have much easier-to-use APIs. We recommend using **RtcTokenBuilder.h** for generating an RTC token or **RtmTokenBuilder.h** for an RTM token.