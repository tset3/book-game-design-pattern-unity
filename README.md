# 蔡升达-设计模式与游戏完美开发
## 目录
```
第1篇 设计模式与游戏设计

第1章 游戏实现中的设计模式 2

1.1 设计模式的起源 2

1.2 软件的设计模式是什么？ 3

1.3 面向对象设计中常见的设计原则 4

1.4 为什么要学习设计模式 7

1.5 游戏程序设计与设计模式 8

1.6 模式的应用与学习方式

1.7 结论 11

第2章 游戏范例说明 12

2.1 游戏范例 12

2.2GoF的设计模式范例 15

第2篇 基础系统

第3章 游戏场景的转换——状态模式（State） 20

3.1 游戏场景 20

3.1.1场景的转换 20

3.1.2游戏场景可能的实现方式 23

3.2 状态模式（State） 24

3.2.1状态模式（State）的定义 24

3.2.2状态模式（State）的说明 25

3.2.3状态模式（State）的实现范例 25

3.3 使用状态模式（State）实现游戏场景的转换 28

3.3.1SceneState的实现 28

3.3.2实现说明 29

3.3.3使用状态模式（State）的优点 35

3.3.4游戏执行流程及场景转换说明 36

3.4状态模式（State）面对变化时 37

3.5 结论 37

第4章 游戏主要类——外观模式（Facade） 39

4.1 游戏子功能的整合 39

4.2 外观模式（Facade） 41

4.2.1外观模式（Facade）的定义 41

4.2.2外观模式（Facade）的说明 42

4.2.3外观模式（Facade）的实现说明 43

4.3 使用外观模式（Facade）实现游戏主程序 44

4.3.1游戏主程序架构设计 44

4.3.2实现说明 45

4.3.3使用外观模式（Facade）的优点 47

4.3.4实现外观模式（Facade）时的注意事项 48

4.4 外观模式（Facade）面对变化时 48

4.5 结论 48

第5章 获取游戏服务的对象——单例模式（Singleton） 50

5.1 游戏实现中的对象 50

5.2 单例模式（Singleton） 51

5.2.1单例模式（Singleton）的定义 51

5.2.2单例模式（Singleton）的说明 51

5.2.3单例模式（Singleton）的实现范例 52

5.3 使用单例模式（Singleton）获取的游戏服务对象53

5.3.1游戏服务类的单例模式实现 53

5.3.2实现说明 54

5.3.3使用单例模式（Singleton）后的比较 55

5.3.4反对使用单例模式（Singleton）的原因 55

5.4 少用单例模式（Singleton）时如何方便地引用到单一对象 58

5.5 结论 63

第6章 游戏内各系统的整合——中介者模式（Mediator） 64

6.1 游戏系统之间的沟通 64

6.2 中介者模式（Mediator） 68

6.2.1中介者模式（Mediator）的定义 69

6.2.2中介者模式（Mediator）的说明 69

6.2.3中介者模式（Mediator）的实现范例 69

6.3 中介者模式（Mediator）作为系统之间的沟通接口72

6.3.1使用中介者模式（Mediator）的系统架构 73

6.3.2实现说明 73

6.3.3使用中介者模式（Mediator）的优点 79

6.3.4实现中介者模式（Mediator）时的注意事项 79

6.4 中介者模式（Mediator）面对变化时 80

6.5 结论 80

第7章 游戏的主循环——GameLoop 82

7.1GameLoop由此开始 82

7.2 怎么实现游戏循环（GameLoop） 84

7.3 在Unity3D中实现游戏循环 85

7.4P级阵地的游戏循环 89

7.5 结论 92

第3篇 角色的设计

第8章 角色系统的设计分析 94

8.1 游戏角色的架构 94

8.2 角色类的规划 95

第9章 角色与的实现——桥接模式（Bridge） 98

9.1 角色与的关系 98

9.2 桥接模式（Bridge） 3

9.2.1桥接模式（Bridge）的定义 3

9.2.2桥接模式（Bridge）的说明 7

9.2.3桥接模式（Bridge）的实现范例 8

9.3 使用桥接模式（Bridge）实现角色与接口1

9.3.1角色与接口设计 1

9.3.2实现说明 111

9.3.3使用桥接模式（Bridge）的优点 116

9.3.4实现桥接模式（Bridge）的注意事项 116

9.4 桥接模式（Bridge）面对变化时 116

9.5 结论 117

第章 角色属性的计算——策略模式（Strategy） 118

.1角色属性的计算需求 118

.2策略模式（Strategy） 121

.2.1策略模式（Strategy）的定义 122

.2.2策略模式（Strategy）的说明 122

.2.3策略模式（Strategy）的实现范例 123

.3使用策略模式（Strategy）实现攻击计算 124

.3.1攻击流程的实现 125

.3.2实现说明 125

.3.3使用策略模式（Strategy）的优点 132

.3.4实现策略模式（Strategy）时的注意事项 133

.4策略模式（Strategy）面对变化时 134

.5结论 135

第11章 攻击特效与击中反应——模板方法模式（Template Method） 137

11.1的攻击流程 137

11.2模板方法模式（Template Method） 139

11.2.1模板方法模式（Template Method）的定义 139

11.2.2模板方法模式（Template Method）的说明 141

11.2.3模板方法模式（Template Method）的实现范例 141

11.3使用模板方法模式实现攻击与击中流程 142

11.3.1攻击与击中流程的实现 143

11.3.2实现说明 143

11.3.3运用模板方法模式（Template Method）的优点 145

11.3.4修改击中流程的实现 145

11.4模板方法模式（Template Method）面对变化时 147

11.5结论 149

第12章 角色AI——状态模式（State） 150

12.1角色的AI 150

12.2状态模式（State） 158

12.3使用状态模式（State）实现角色AI 159

12.3.1角色AI的实现 159

12.3.2实现说明 160

12.3.3使用状态模式（State）的优点 169

12.3.4角色AI执行流程 169

12.4状态模式（State）面对变化时 170

12.5结论 172

第13章 角色系统 174

13.1角色类 174

13.2游戏角色管理系统 176

第4篇 角色的产生

第14章 游戏角色的产生——工厂方法模式（Factory Method） 183

14.1产生角色 183

14.2工厂方法模式（Factory Method） 188

14.2.1工厂方法模式（Factory Method）的定义 188

14.2.2工厂方法模式（Factory Method）的说明 189

14.2.3工厂方法模式（Factory Method）的实现范例 189

14.3使用工厂方法模式（Factory Method）产生角色对象 195

14.3.1角色工厂类 195

14.3.2实现说明 196

14.3.3使用工厂方法模式（Factory Method）的优点 199

14.3.4工厂方法模式（Factory Method）的实现说明 199

14.4工厂方法模式（Factory Method）面对变化时 203

14.5结论 205

第15章 角色的组装——建造者模式（Builder） 206

15.1角色功能的组装 206

15.2建造者模式（Builder） 213

15.2.1建造者模式（Builder）的定义 213

15.2.2建造者模式（Builder）的说明 214

15.2.3建造者模式（Builder）的实现范例 215

15.3使用建造者模式（Builder）组装角色的各项功能 217

15.3.1角色功能的组装 218

15.3.2实现说明 219

15.3.3使用建造者模式（Builder）的优点 226

15.3.4角色建造者的执行流程 226

15.4建造者模式（Builder）面对变化时 227

15.5结论 228

第16章 游戏属性管理功能——享元模式（Flyweight） 229

16.1游戏属性的管理 229

16.2享元模式（Flyweight） 236

16.2.1享元模式（Flyweight）的定义 236

16.2.2享元模式（Flyweight）的说明 237

16.2.3享元模式（Flyweight）的实现范例 238

16.3使用享元模式（Flyweight）实现游戏 242

16.3.1SceneState的实现 242

16.3.2实现说明 245

16.3.3使用享元模式（Flyweight）的优点 250

16.3.4享元模式（Flyweight）的实现说明 250

16.4享元模式（Flyweight）面对变化时 252

16.5结论 252

第5篇 战争开始

第17章 Unity3D的界面设计——组合模式（Composite） 254

17.1玩家界面设计 254

17.2组合模式（Composite） 259

17.2.1组合模式（Composite）的定义 259

17.2.2组合模式（Composite）的说明 260

17.2.3组合模式（Composite）的实现范例 261

17.2.4分了两个子类但是要使用同一个操作界面 264

17.3Unity3D游戏对象的分层式管理功能 265

17.3.1游戏对象的分层管理 265

17.3.2正确有效地获取UI的游戏对象 266

17.3.3游戏用户界面的实现 267

17.3.4兵营界面的实现 269

17.4结论 274

第18章 兵营系统及兵营信息显示276

18.1兵营系统 276

18.2兵营系统的组成 277

18.3初始兵营系统 281

18.4兵营信息的显示流程 287

第19章 兵营训练单位——命令模式（Command） 288

19.1兵营界面上的命令 288

19.2命令模式（Command） 291

19.2.1命令模式（Command）的定义 291

19.2.2命令模式（Command）的说明 294

19.2.3命令模式（Command）的实现范例 294

19.3使用命令模式（Command）实现兵营训练角色 297

19.3.1训练命令的实现 297

19.3.2实现说明 298

19.3.3执行流程 302

19.3.4实现命令模式（Command）时的注意事项 303

19.4命令模式（Command）面对变化时 305

19.5结论 306

第20章 关卡设计——责任链模式（Chainof Responsibility） 307

20.1关卡设计 307

20.2责任链模式（Chain of Responsibility） 312

20.2.1责任链模式（Chain of Responsibility）的定义 312

20.2.2责任链模式（Chain of Responsibility）的说明 314

20.2.3责任链模式（Chain of Responsibility）的实现范例 314

20.3使用责任链模式（Chain of Responsibility）实现关卡系统 317

20.3.1关卡系统的设计 317

20.3.2实现说明 318

20.3.3使用责任链模式（Chain of Responsibility）的优点 329

20.3.4实现责任链模式（Chain of Responsibility）时的注意事项 329

20.4责任链模式（Chain of Responsibility）面对变化时 330

20.5结论 332

第6篇 辅助系统

第21章 成就系统—观察者模式（Observer） 334

21.1成就系统 334

21.2观察者模式（Observer） 338

21.2.1观察者模式（Observer）的定义 338

21.2.2观察者模式（Observer）的说明 340

21.2.3观察者模式（Observer）的实现范例 341

21.3使用观察者模式（Observer）实现成就系统 344

21.3.1成就系统的新架构 344

21.3.2实现说明 346

21.3.3使用观察者模式（Observer）的优点 358

21.3.4实现观察者模式（Observer）时的注意事项 358

21.4观察者模式（Observer）面对变化时 359

21.5结论 361

第22章 存盘功能—备忘录模式（Memento） 362

22.1存储成就记录 362

22.2备忘录模式（Memento） 366

22.2.1备忘录模式（Memento）的定义 366

22.2.2备忘录模式（Memento）的说明 367

22.2.3备忘录模式（Memento）的实现范例 367

22.3使用备忘录模式（Memento）实现成就记录的保存 371

22.3.1成就记录保存的功能设计 371

22.3.2实现说明 371

22.3.3使用备忘录模式（Memento）的优点 374

22.3.4实现备忘录模式（Memento）的注意事项374

22.4备忘录模式（Memento）面对变化时 374

22.5结论 375

第23章 角色信息查询—访问者模式（Visitor） 376

23.1角色信息的提供 376

23.2访问者模式（Visitor） 385

23.2.1访问者模式（Visitor）的定义 386

23.2.2访问者模式（Visitor）的说明 390

23.2.3访问者模式（Visitor）的实现范例 392

23.3使用访问者模式（Visitor）实现角色信息查询 397

23.3.1 角色信息查询的实现设计 397

23.3.2实现说明 398

23.3.3使用访问者模式（Visitor）的优点 405

23.3.4实现访问者模式（Visitor）时的注意事项 405

23.4访问者模式（Visitor）面对变化时 405

23.5结论 408

第7篇 调整与优化

第24章 前缀字尾—装饰模式（Decorator） 4

24.1前缀后缀系统 4

24.2装饰模式（Decorator） 415

24.2.1装饰模式（Decorator）的定义 415

24.2.2装饰模式（Decorator）的说明 418

24.2.3装饰模式（Decorator）的实现范例 419

24.3使用装饰模式（Decorator）实现前缀后缀的功能 422

24.3.1前缀后缀功能的架构设计 423

24.3.2实现说明 423

24.3.3使用装饰模式（Decorator）的优点 433

24.3.4实现装饰模式（Decorator）时的注意事项 433

24.4装饰模式（Decorator）面对变化时 434

24.5结论 435

第25章 俘兵—适配器模式（Adapter） 436

25.1游戏的宠物系统 436

25.2适配器模式（Adapter） 440

25.2.1适配器模式（Adapter）的定义 440

25.2.2适配器模式（Adapter）的说明 441

25.2.3适配器模式（Adapter）的实现范例 441

25.3使用适配器模式（Adapter）实现俘兵系统 443

25.3.1俘兵系统的架构设计 443

25.3.2实现说明 443

25.3.3与俘兵相关的新增部分 445

25.3.4使用适配器模式（Adapter）的优点 450

25.4适配器模式（Adapter）面对变化时 450

25.5结论 451

第26章 加载速度的优化—代理模式（Proxy） 453

26.1后的系统优化 453

26.2代理模式（Proxy） 457

26.2.1代理模式（Proxy）的定义 458

26.2.2代理模式（Proxy）的说明 458

26.2.3代理模式（Proxy）的实现范例 459

26.3使用代理模式（Proxy）测试和优化加载速度 460

26.3.1优化加载速度的架构设计 460

26.3.2实现说明 461

26.3.3使用代理模式（Proxy）的优点 464

26.3.4实现代理模式（Proxy）时的注意事项 464

26.4代理模式（Prory）面对变化时 466

26.5结论 466

第8篇 未明确使用的模式

第27章 迭代器模式（Iterator）、原型模式（Prototype）和解释器模式（Interpreter） 468

27.1迭代器模式（Iterator） 468

27.2原型模式（Prototype） 469

27.3解释器模式（Interpreter） 471

第28章 抽象工厂模式（AbstractFactory） 472

28.1抽象工厂模式（Abstract Factory）的定义 472

28.2抽象工厂模式（Abstract Factory）的实现 473

28.3可应用抽象工厂模式的场合 476
```
