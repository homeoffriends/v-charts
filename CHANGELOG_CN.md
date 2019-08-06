<a name="1.0.1"></a>
# [1.0.1](https://github.com/ElemeFE/v-charts/compare/v1.0.0...v1.0.1) (2019-07-23)

### Features
* **core:** 添加对元素的resize监听

<a name="1.0.2"></a>
# [1.0.2](https://github.com/ElemeFE/v-charts/compare/v1.0.1...v1.0.2) (2019-08-06)

### Features
* **core:** 支持更通用的数据格式，我们称为CommonData,样例数据如下,依然用data属性，我们在内部做了适配:
     var commonData = {
        columns: [
          {
            field: "date",
            name: "日期",
            fieldType: "Date",
            unit: "",
          },
          {
            field: "visitUserNum",
            name: "访问用户",
            fieldType: "Integer",
            unit: "",
          },
          {
            field: "buyUserNum",
            name: "下单用户",
            fieldType: "Integer",
            unit: "",
          },
        ],
        rows: [
          { date: "1/1", visitUserNum: 1393, buyUserNum: 1093 },
          { date: "1/2", visitUserNum: 3530, buyUserNum: 3230 },
          { date: "1/3", visitUserNum: 2923, buyUserNum: 2623 },
          { date: "1/4", visitUserNum: 1723, buyUserNum: 1423 },
          { date: "1/5", visitUserNum: 3792, buyUserNum: 3492 },
          { date: "1/6", visitUserNum: 4593, buyUserNum: 4293 },
        ],
      }
