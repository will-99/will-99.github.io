### 一、运维场景列表
###### 页面路径 （运维场景——运维场景列表）
##### 操作指令
**1. 查看XX的运维场景**
```
// eg.查看逻辑图的运维场景
{
    id: 1,  // 口令id
    question: "查看逻辑图的运维场景。", // 用户指令
    answer: "已为您显示运维图的运维场景。", // 机器人应答
    url: "/jsp/pages/configmgt/flowChart/sceneGraph/flowChartEdit.jsp",  // 页面的地址
    structureId: "D882FFABB439D9E46DC0C9087344F832",    // 系统架构id
    pageTitle: "逻辑图",    // 运维场景的名称
    viewId: "5BAEF6ABC2F43AA46D9D849FDB7CCF74"  //  运维场景的id
}
```
**2. 查看XX运维场景XX的健康评分**
```
// eg.查看逻辑图的生产数据库1的健康评分
{
    id: 2,  // 口令id
    question: "查看逻辑图的生产数据库1的健康评分。", // 用户指令
    answer: "已为您显示逻辑图的生产数据库1的健康评分。", // 机器人应答
    url: "/jsp/pages/configmgt/flowChart/healthScore_znyw/healthScore_znyw.jsp",  // 页面的地址
    elementId: "4E5E100016A15472703F4F533DD57474",  // 对象的elementId
    targetId: "yt_10-11-10-00136-JS:60_60_60_117",   // 对象的targetId
}
```

### 二、健康模型
###### 页面路径 （健康模型——系统模型）
##### 操作指令
**1. 查看XX的健康模型**
```
// eg.查看95598业务支持系统健康模型
{
    id: 3,  // 口令id
    question: "查看95598业务支持系统健康模型。", // 用户指令
    answer: "已为您显示95598业务支持系统健康模型。", // 机器人应答
    url: "/jsp/pages/configmgt/flowChart/healthModel/healthModelScore_v2.jsp",  // 页面的地址
    modelId: "E820AC369B3E723109AC187EB5682C86" // 健康模型id
}
```

### 三、性能评分
###### 页面路径 （应用墙）
##### 操作指令
**1. 查看XX的性能评分**
```
// eg.查看95598业务支持系统最近24小时按照区间内最大值排名的性能评分
{
    id: 4,  // 口令id
    question: "查看95598业务支持系统最近24小时按照区间内最大值排名的性能评分。", // 用户指令
    answer: "已为您显示95598业务支持系统最近24小时按照区间内最大值排名的性能评分。", // 机器人应答
    url: "/jsp/pages/performanceRank/performanceRank.jsp",  // 页面的地址
    focusedStrcutureId: "D882FFABB439D9E46DC0C9087344F832", // 系统架构id
    focusedStrcutureName: "95598业务支持系统",  // 系统架构名称
    rankType: "max",    // 排名类型
    indexSel: "",   // 指标id
    startTime: "",  // 开始时间
    endTime: "" // 结束时间
}
```
**2. 查看XX的XX的指标评分**
```
// eg.查看95598业务支持系统的配抢数据库服务器1的指标评分
{
    id: 5,  // 口令id
    question: "查看95598业务支持系统的配抢数据库服务器1的指标评分。", // 用户指令
    answer: "已为您显示95598业务支持系统的配抢数据库服务器1的指标评分。", // 机器人应答
    url: "/jsp/pages/performanceRank/performanceRank.jsp",  // 页面的地址
    focusedStrcutureId: "D882FFABB439D9E46DC0C9087344F832", // 系统架构id
    focusedStrcutureName: "95598业务支持系统",  // 系统架构名称
    chosenElementId: "CDA5EBD99BCE1B5473FCC7C7E35D8593",    // 对象的elementId
    chosenElementName: "配抢数据库服务器1", // 对象的名称
    startTime: "",  // 开始时间
    endTime: "" // 结束时间
}
```

### 四、告警管理
###### 页面路径 （告警中心——告警管理）
##### 操作指令
**1. 查看告警信息**
```
// eg.查看告警信息
{
    id: 6,  // 口令id
    question: "查看告警信息。", // 用户指令
    answer: "已为您显示告警信息。", // 机器人应答
    url: "/jsp/pages/warnList/warnHandleList.jsp",  // 页面的地址
    device_name_srch: "配抢数据库服务器1",  // 运维对象名称
    device_type_srch: "server_3",   // 对象类型
    process_status_srch: "0",   // 处理状态
    warn_level_srch: "1",   // 告警等级
    startTime: "2020-04-13 11:17",  // 开始时间
    endTime: "2020-04-14 11:17" // 结束时间
}
```

### 五、单指标分析
###### 页面路径 （数据集市——单指标分析）
##### 操作指令
**1. 查看XX的XX的指标XX的单指标分析。**
```
// eg.查看告警信息
{
    id: 7,  // 口令id
    question: "查看95598业务支持系统的配抢数据库服务器1的指标CPU used今天的单指标分析。", // 用户指令
    answer: "已为您显示95598业务支持系统的配抢数据库服务器1的指标CPU used今天的单指标分析。", // 机器人应答
    url: "/jsp/pages/indexDataInWeek/indexDataInWeek.jsp",  // 页面的地址
    search_structure: "D882FFABB439D9E46DC0C9087344F832",   // 系统架构id
    search_element: "CDA5EBD99BCE1B5473FCC7C7E35D8593", // 对象elementId
    search_index: "PM-00-00-010-04",    // 指标id
    start_time: "2020-04-16"    // 时间
}
```

### 六、多指标分析
###### 页面路径 （数据集市——多指标分析）
##### 操作指令
**1. 查看XX的XX的指标XX的多指标分析。**
```
// eg.查看告警信息
{
    id: 8,  // 口令id
    question: "查看95598业务支持系统的配抢数据库服务器1的指标CPU used和Ioawait从4月13日到4月14日的多指标分析。", // 用户指令
    answer: "已为您显示95598业务支持系统的配抢数据库服务器1的指标CPU used和Ioawait从4月13日到4月14日的多指标分析。", // 机器人应答
    url: "/jsp/pages/publiccharts/publiccharts.jsp",  // 页面的地址
    chartArr: [{
        search_structure: "D882FFABB439D9E46DC0C9087344F832",   // 系统架构id
        search_element: "CDA5EBD99BCE1B5473FCC7C7E35D8593", // 对象elementId
        search_index: "PM-00-00-010-04",    // 指标id
        start_time: "2020-04-13 00:00:00",  // 开始时间
        end_time: "2020-04-14 00:00:00" // 结束时间
    }, {
        search_structure: "D882FFABB439D9E46DC0C9087344F832",
        search_element: "CDA5EBD99BCE1B5473FCC7C7E35D8593",
        search_index: "PM-00-00-010-20",
        start_time: "2020-04-13 00:00:00",
        end_time: "2020-04-14 00:00:00"
    }]  // 多指标信息数组
}
```

### 七、业务流程 | 事务分析 | 逻辑拓扑
###### 页面路径 （首页）
##### 操作指令
**1. 查看XX的业务流程 | 事务分析 | 逻辑拓扑。**
```
// eg.查看95598业务支持系统业务流程
{
    id: 9,  // 口令id
    question: "查看95598业务支持系统业务流程。", // 用户指令
    answer: "已为您显示95598业务支持系统的业务流程。", // 机器人应答
    url: "/jsp/pages/configmgt/flowChart/sceneGraph/flowChartEdit.jsp",  // 页面的地址
    viewId: "784F8A8F50C2F95482E2A4EB2338F883", // 图层id
    pageTitle: "业务流程"   // 页面名称
}
```

### 八、物理链路
###### 页面路径 （首页）
##### 操作指令
**1. 查看XX的物理链路。**
```
// eg.查看95598业务支持系统物理链路
{
    id: 10,  // 口令id
    question: "查看95598业务支持系统物理链路。", // 用户指令
    answer: "已为您显示95598业务支持系统的物理链路。", // 机器人应答
    url: "/jsp/pages/configmgt/flowChart/systemArchitecture/architectureDiagram.jsp",  // 页面的地址
    structureId: "D882FFABB439D9E46DC0C9087344F832", // 图层id
    pageTitle: "物理链路"   // 页面名称
}
```
