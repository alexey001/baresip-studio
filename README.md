This is very basic Android Studio project implementing baresip
(https://github.com/alfredh/baresip) based SIP User Agent.

Currently supports voice calls and messages with TLS transport,
voicemail MWI, PCMU/PCMA and opus voice codecs, as well as ZRTP and
(DTLS) SRTP media encapsulation.

Motivated by need for secure SIP user agent for Android that does not
depend on third party push notification services.

The static libraries and include files in distribution directory have
been produced using https://github.com/juha-h/libbaresip-android.
Before making libbaresip, apply reg.c-patch to re/src/sipreg/reg.c.  The
patch is needed due to re timer sometimes firing too late.

After cloning the project, in android-studio:

- Open an existing Android Studio project

- File -> Invalidate Caches / Restart -> Invalidate & Restart

Now available also in Google Play store.

Feedback welcome.
