<!--
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->
定制 Superset
=========

本项目Folk自 apache-superset ，针对部分在实际使用中遇到的场景需要进行定制

<img
  src="https://cloud.githubusercontent.com/assets/130878/20946612/49a8a25c-bbc0-11e6-8314-10bef902af51.png"
  alt="Superset"
  width="500"
/>


## Screenshots & Gifs

**View Dashboards**

<kbd><img title="View Dashboards" src="https://raw.githubusercontent.com/apache/incubator-superset/master/superset-frontend/images/screenshots/bank_dash.png"></kbd><br/>

**Slice & dice your data**


## 定制了什么

* 汉化
* 时间周期定制 -- 针对Oracle 数据源
    
    * 数据粒度周 ，切换为固定每周一 进行分组，方便各个数据用户按照自然周分析，也方便用户取数写周报
    * 默认是 ww 切换为 iw

|关键字|含义|英文|
|---|---|---|
|ww|按年度1月1日的第一天为每周第一天|Same day of the week as the first day of the year|
|iw|每周一|Same day of the week as the first day of the ISO week, which is Monday|
|w|按月份1日的第一天作为每周第一天|Same day of the week as the first day of the month|


## Get Help

* [Stackoverflow tag](https://stackoverflow.com/questions/tagged/apache-superset)
* [Join Community Slack](https://join.slack.com/t/apache-superset/shared_invite/enQtNDMxMDY5NjM4MDU0LWJmOTcxYjlhZTRhYmEyYTMzOWYxOWEwMjcwZDZiNWRiNDY2NDUwNzcwMDFhNzE1ZmMxZTZlZWY0ZTQ2MzMyNTU)
* [Mailing list](https://lists.apache.org/list.html?dev@superset.apache.org)


## Contributor Guide

Interested in contributing? Check out
[Contributing.MD](https://github.com/apache/superset/blob/master/CONTRIBUTING.md) to learn how to contribute and best practices.


## Resources

## License

```
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
```
