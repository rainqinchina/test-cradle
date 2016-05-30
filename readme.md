1. gradle dist test
2. gradle dist -x test
3. gradle dist --continue
4. gradle di // abbreviated task name
4. gradle cT // abbreviated task name
5. gradle -q -b subdir/myproject.gradle hello // 使用自定义的build文件构建项目
6. gradle -q -p subdir hello // subduer下面有个build.grade的文件，此命令才有用
7. gradle --rerun-tasks dis 
8. gradle -q projects // 查看工程信息
9. description = 'The shared API for the application' //构建文件中增加项目描述
10. gradle -q tasks // 查看默认的task
11. gradle -q tasks --all
12. gradle -q help --task dists //查看详情
13. gradle -q dependencies api:dependencies webapp:dependencies // 查看依赖
14. gradle -q api:dependencies --configuration testCompile //单独查看
15.  gradle -q webapp:dependencyInsight --dependency groovy --configuration compile
	// 查看依赖
16. gradle -q api:properties // 查看properties
17. gradle buildEnvironment
18. gradle -m clean compile //不执行，但感兴趣