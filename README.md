<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcW5mOGVkY2J1Z2J4d2R0dWJ1aXJqY2V4eGZ2bHZqZzRlZGZ6eWZ6biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/qgQUggAC3Pfv687qPC/giphy.gif" width="200"/>
  <h1>👋 Hey there, I'm Keneret</h1>
  <h3>🤖 Robotics Engineer | 🧠 AI Enthusiast | 💻 Full-Stack Developer | 👨‍🎓 Student </h3>
</div>

---

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=22D3F7&center=true&vCenter=true&width=435&lines=Building+the+future+with+circuits+and+code;Turning+coffee+into+robotic+solutions;ROS2+%7C+Computer+Vision+%7C+Embedded+Systems" alt="Typing animation" />
</p>

---

### 🛠️ My Tech Stack

#### 🤖 Robotics & Embedded
<p>
  <img src="https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white" />
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white" />
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" />
  <img src="https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
    <img src="https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=opencv&logoColor=black" alt="YOLO" />

</p>

#### 💻 Programming Languages
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
</p>

#### 🌐 Web & Mobile
<p>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
<!--   <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" /> -->
</p>

---

### 🚀 Featured Projects

#### 🤖 Sweepy - Autonomous Beach Cleaning Robot
```python
class Sweepy:
    def __init__(self):
        self.vision = YOLOv8()
        self.nav = ROS2Navigation()
        self.actuators = RoboticArm()
    
    def clean_beach(self):
        while True:
            trash = self.vision.detect_trash()
            if trash:
                path = self.nav.plan_path(trash.position)
                self.nav.follow_path(path)
                self.actuators.collect(trash)
```
#### 🤖 Sweepy - Autonomous Beach Cleaning Robot
```Dart
class STNSApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MultiProvider(
      providers: [
        ChangeNotifierProvider(create: (_) => AuthProvider()),
        ChangeNotifierProvider(create: (_) => DataProvider()),
      ],
      child: MaterialApp(
        title: 'STNS',
        theme: AppTheme.lightTheme,
        home: AuthWrapper(),
        navigatorObservers: [AnalyticsObserver()],
      ),
    );
  }
}

🌌 Late Night Coding   ███████████████████░░   85% 
☕ Coffee Consumed     █████████████████████   100%
🤖 ROS2 Nodes         ████████████░░░░░░░░░   60%
🐍 Python Scripts     █████████████████░░░░   75%
🔧 Hardware Debugging ████████░░░░░░░░░░░░░   40%
