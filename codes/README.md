# fuzzing code samples

个人`fuzz`代码积累

## 项目

[chromium相关fuzz代码](https://cs.chromium.org/search/?q=file:.*fuzzer.*.cc&type=cs)：具有很大的参考价值

[v8 fuzzer代码](https://github.com/v8/v8/tree/master/test/fuzzer)

[google oss-fuzz](https://github.com/google/oss-fuzz): 强烈推荐挨个项目代码读

`oss-fuzz`可以作为每天睡前读物
具体方法：根据`projects`下面的项目，到每个具体的项目下看`fuzzer`代码,因为这些项目都是质量比较高的开源项目,所以一般情况下`fuzzer`代码质量也会比较高
也可以学习各种`fuzz`方式