<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:02569B,50:0175C2,100:13B9FD&text=Sohaib%20Mahmoud&fontColor=ffffff&fontSize=52&fontAlignY=34&desc=Mobile%20Software%20Engineer%20·%20Flutter&descSize=18&descAlignY=54&animation=fadeIn" />

<div align="center">

### Shipping production Flutter across mobile and web since 2023

Five apps live on the App Store and Google Play, serving 20,000+ users across Egypt and the Gulf.
Specialising in real-time systems, native platform integration, and Arabic-first product design.

<br/>

<a href="https://www.linkedin.com/in/sohaib-mahmoud-814aa6177/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:sohaibmahmoud06@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://your-portfolio-link.com"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>

</div>

<br/>

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="28"> &nbsp;About Me

```dart
class Sohaib extends MobileEngineer {
  @override
  final String location = 'Cairo, Egypt 🇪🇬';

  @override
  final String company = 'Hatching Ducks';

  @override
  List<String> get focus => [
        'Real-time systems — WebSockets, SSE, multiplayer state sync',
        'Native bridging — MethodChannel into the Android SDK',
        'Payments & security — gateways, Cloud Functions, encryption',
        'Arabic-first products — RTL from the design system up',
      ];

  @override
  Future<Product> build(Idea idea) async {
    final architecture = CleanArchitecture(state: Bloc());
    final product = await architecture.ship(idea);

    return product
      ..monitor(Sentry())
      ..iterate();
  }
}
```

> I build the parts of mobile that aren't UI — synchronizing state across four clients in real time, bridging into platform APIs when the plugin ecosystem runs out, and making sure a payment can't be charged twice. Most of my work ships to Arabic-speaking markets, so RTL isn't an afterthought in anything I design.

<br/>

## <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="28"> &nbsp;Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=flutter,dart,java,python,c,cpp,androidstudio,firebase&theme=dark" />
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,supabase,sqlite,postgres,git,github,vscode,postman&theme=dark" />

</div>

<br/>

<div align="center">

**📱 &nbsp;Mobile**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Bloc](https://img.shields.io/badge/Bloc_/_Cubit-1E88E5?style=flat-square&logo=dart&logoColor=white)
![RxDart](https://img.shields.io/badge/RxDart-B7178C?style=flat-square&logo=reactivex&logoColor=white)
![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-00897B?style=flat-square&logo=buffer&logoColor=white)
![MethodChannel](https://img.shields.io/badge/MethodChannel-3DDC84?style=flat-square&logo=android&logoColor=white)
![Native Android](https://img.shields.io/badge/Native_Android-F89820?style=flat-square&logo=openjdk&logoColor=white)

**☁️ &nbsp;Backend & Cloud**

![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Firestore](https://img.shields.io/badge/Firestore-FF8F00?style=flat-square&logo=firebase&logoColor=white)
![Cloud Functions](https://img.shields.io/badge/Cloud_Functions-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![FCM](https://img.shields.io/badge/FCM-FFA000?style=flat-square&logo=firebase&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-009688?style=flat-square&logo=fastapi&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)
![SSE](https://img.shields.io/badge/SSE-5A0FC8?style=flat-square&logo=serverfault&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PocketBase](https://img.shields.io/badge/PocketBase-B8DBE4?style=flat-square&logo=pocketbase&logoColor=black)

**🚀 &nbsp;Delivery & Ops**

![Fastlane](https://img.shields.io/badge/Fastlane-00F200?style=flat-square&logo=fastlane&logoColor=black)
![CI/CD](https://img.shields.io/badge/CI/CD-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Shorebird](https://img.shields.io/badge/Shorebird_Code_Push-13B9FD?style=flat-square&logo=flutter&logoColor=white)
![Build Flavors](https://img.shields.io/badge/Build_Flavors-6C63FF?style=flat-square&logo=gradle&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)
![Crashlytics](https://img.shields.io/badge/Crashlytics-FF6F00?style=flat-square&logo=firebase&logoColor=white)
![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=appstore&logoColor=white)
![Play Store](https://img.shields.io/badge/Play_Store-414141?style=flat-square&logo=googleplay&logoColor=white)

</div>

<br/>

## <img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="28"> &nbsp;Selected Work

<table>
<tr>
<td width="50%" valign="top">

### 🎮 RKZ — Trivia Game Platform

> Arabic trivia game across iOS, Android and Web, with a Flutter Web admin dashboard. **20,000+ players.**

Migrated the entire backend from Firebase to REST without rewriting a UI layer. Real-time spectating over SSE, two payment gateways proxied through Cloud Functions, multi-device session security.

![Flutter](https://img.shields.io/badge/-Flutter-05122A?style=flat&logo=flutter&logoColor=02569B)
![Firebase](https://img.shields.io/badge/-Firebase-05122A?style=flat&logo=firebase&logoColor=FFCA28)
![Node](https://img.shields.io/badge/-Node.js-05122A?style=flat&logo=node.js&logoColor=339933)

</td>
<td width="50%" valign="top">

### 📚 El Marwa — E-Learning Platform

> Arabic-first platform for a physics education center. Paid courses, live sessions, quizzes, parent portal.

DRM-style content protection with device binding, screenshot blocking and AES-encrypted offline PDFs. Forked two video players for adaptive resolution switching.

![Flutter](https://img.shields.io/badge/-Flutter-05122A?style=flat&logo=flutter&logoColor=02569B)
![Firebase](https://img.shields.io/badge/-Firebase-05122A?style=flat&logo=firebase&logoColor=FFCA28)
![Payments](https://img.shields.io/badge/-Fawaterak-05122A?style=flat&logo=stripe&logoColor=635BFF)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ MobiWall — Parental Control

> Dual-role Android app with separate parent and child modes.

Native Android layer bridged over MethodChannel — AccessibilityService, DevicePolicyManager, UsageStatsManager. ML usage classification and a smartwatch SOS pipeline.

![Flutter](https://img.shields.io/badge/-Flutter-05122A?style=flat&logo=flutter&logoColor=02569B)
![Java](https://img.shields.io/badge/-Java-05122A?style=flat&logo=openjdk&logoColor=F89820)
![HuggingFace](https://img.shields.io/badge/-Hugging%20Face-05122A?style=flat&logo=huggingface&logoColor=FFD21E)

</td>
<td width="50%" valign="top">

### 🃏 Shal7 — Multiplayer Card Game

> Real-time 2v2 card game. Four concurrent clients, sub-second latency.

Host-authoritative state model eliminating duplicate-play and race conditions. AI bots fill empty seats. Shipped with Shorebird code-push.

![Flutter](https://img.shields.io/badge/-Flutter-05122A?style=flat&logo=flutter&logoColor=02569B)
![Firebase](https://img.shields.io/badge/-Firebase-05122A?style=flat&logo=firebase&logoColor=FFCA28)
![Lottie](https://img.shields.io/badge/-Lottie-05122A?style=flat&logo=airbnb&logoColor=FF5A5F)

</td>
</tr>
</table>

<br/>

## <img src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif" width="28"> &nbsp;GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=sohaib077&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=13B9FD&icon_color=02569B" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sohaib077&layout=compact&langs_count=8&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=13B9FD" />

</div>

<br/>

## <img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="28"> &nbsp;Contribution Graph

<div align="center">

![snake animation](https://raw.githubusercontent.com/sohaib077/sohaib077/output/snake.svg)

</div>

<br/>

<div align="center">

### 💬 Open to Flutter roles — remote, hybrid or Cairo-based

*"Ship it, monitor it, then make it faster."*

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:13B9FD,50:0175C2,100:02569B&section=footer" />
