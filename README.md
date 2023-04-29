# GitHub_Homework_2


1. На локальном репозитории сделать ветки для:
- Postman 

      git branch Postman	
- Jmeter 

      git branch Jmeter
- CheckLists 

      git branch CheckLists
- Bag Reports 
      
      git branch Bag_Reports 
- SQL 

      git branch SQL
- Charles 
      
      git branch Charles
- Mobile testing 
      
      git branch Mobile_testing

2. Запушить все ветки на внешний репозиторий
- Postman 

      git push --set-upstream origin Postman	
- Jmeter 

      git push --set-upstream origin Jmeter
- CheckLists 

      git push --set-upstream origin CheckLists
- Bag Reports 

      git push --set-upstream origin Bag_Reports
- SQL 

      git push --set-upstream origin SQL
- Charles 

      git push --set-upstream origin Charles
- Mobile testing 

      git push --set-upstream origin Mobile_testing


3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта.

       git checkout Bag_Reports
       touch bag-report.txt
       nano bag-report.txt
4. Запушить структуру багрепорта на внешний репозиторий.

       git add bag-report.txt
       git commit -m "add bag-report"
       git push
5. Вмержить ветку Bag Reports в Main

       git checkout main
       git merge Bag_Reports
6. Запушить main на внешний репозиторий.

       git add .
       git commit -m "merge branch Bag_Reports"
       git push
7. В ветке CheckLists набросать структуру чек листа.

       git checkout CheckLists
       touch checklist.txt
       nano checklist.txt
8. Запушить структуру на внешний репозиторий.

       git add checklist.txt
       git commit -m "add checklist.txt"
       git push
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
10. Синхронизировать Внешнюю и Локальную ветки Main

        git checkout main
        git pull
