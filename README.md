# Запуск docker_test

1. Создать в Jenkins задачу Pipeline.
2. В разделе Pipeline установить:
- Definition: Pipeline script from SCM
- SCM: Git
3. В Repository URL указать ссылку на этот репозиторий.

`https://github.com/Egorafnsv/docker_test.git`

4. В Script Path указать имя jenkinsfile: 
> Jenkinsfile.jenkins
5. Сохранить и собрать.