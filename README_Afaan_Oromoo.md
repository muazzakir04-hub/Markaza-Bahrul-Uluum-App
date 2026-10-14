# MARKAZA BAHRUL ULUUM — Appii Barnoota Tajwiidaa

## Wanti ZIP kana keessa jiru
- Android Studio project (Kotlin + WebView)
- Appii barnoota Tajwiidaa offline
- Boqonnaawwan jalqabaa, seerota, fakkeenyota, qormaata fi TTS sagalee bilbilaa
- Kitaaba PDF guutuu kee `app/src/main/assets/kitaaba_tajwiidaa.pdf` keessatti kuufame
- PDF reader native Android (fuula duraa/itti aanu)

## APK ijaaruu
APK duraan ijaarame miti; kun **source project** dha. APK argachuuf:
1. Kompiitara irratti Android Studio install godhi.
2. ZIP kana extract godhi.
3. Android Studio → Open → folder `Markaza_Bahrul_Uluum_Tajwiid_App` filadhu.
4. Gradle sync xumuri; SDK Platform 35 fi Android Gradle Plugin barbaachisan akka buufaman hayyami.
5. Bilbila Android USB debugging waliin wal qunnamsiisi, yookaan emulator filadhu.
6. Run (▶) tuqi, yookaan Build → Build APK(s) filadhu.
7. APK debug yeroo baay'ee `app/build/outputs/apk/debug/app-debug.apk` keessatti argama.
8. APK bilbila irratti fe'uuf file sana gara bilbilaatti ergi; “Install unknown apps” hayyama appii file ittiin banteef kennuu si gaafachuu danda'a.

## Barbaachisummaa / daangaa version 1
- Barnoota web keessaa fi PDF offline hojjetu; internet hin barbaadu.
- Sagaleen barreeffama dubbisu (TTS) voice Android irratti hundaa'a; voice Arabaa buufatame ta'uun barbaachisaa ta'uu danda'a. Kun qara'aa Qur'aanaa sirrii bakka hin bu'u.
- Qabiyyeen Tajwiidaa appii keessaa jalqabaa fi fakkeenya barsiisotaaf qajeelfama dha; sirrummaa qara'aa barsiisaa tajwiidaa qabuun mirkaneessi.
- Sagalee qara'aa Qur'aanaa recorded/verified, logo rasmiin, icon appii fi boqonnaawwan kitaaba hunda irraa sirriitti qindeessuun release itti aanu keessatti dabaluu ni danda'ama.
