## 组件名称: Java Jacoco Test
### Java Jacoco Test:
Java Jacoco代码测试工具, 用于生成代码覆盖率报告

### 组件参数
#### 入参
* `GIT_CLONE_URL` 必填，源代码地址，如为私有仓库需要授权; 如需使用系统关联的git仓库, 可以从系统提供的全局环境变量中获取: ${_WORKFLOW_GIT_CLONE_URL}
* `GIT_REF` 非必填，源代码git目标引用，可以是一个git branch, git tag 或者git commit ID, 默认值master

#### 出参
无

### Tag列表及其Dockerfile链接
* 0.8, latest: [Dockerfile](https://github.com/tencentyun/workflow-components/blob/21d54e12fffca3fb754860336e42f8e1e268830b/java/test/jacoco/Dockerfile)

### 源码地址

Java Jacoco Test: <https://github.com/tencentyun/workflow-components/tree/master/java/test/jacoco>

### 构建
`docker build -t hub.tencentyun.com/tencenthub/java_test_jacoco:latest .`