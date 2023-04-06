# GitHub_HomeWork2
1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
```
git branch <имя_ветки>  
еще есть
git checkout -b <имя_ветки> - сразу создать переместиться
```
2. Запушить все ветки на внешний репозиторий  
```
git push origin -u --all
```
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
```
git checkout BagReports 
cat > Bag1.txt 
tekst baga enter 
ctrl+d
```
4. Запушить структуру багрепорта на внешний репозиторий
```
git add . && git commit -m "text bag" && git push
```
5. Вмержить ветку Bag Reports в Main
```
git checkout main
git merge Bag Reports
```
6. Запушить main на внешний репозиторий.
```
git push
```
7. В ветке CheckLists набросать структуру чек листа
```
cat > cheklist_structure.txt 
tekst enter 
cntrl +d
```
8. Запушить структуру на внешний репозиторий
```
git add . && git commit -m "add text" && git push
```
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
```
зайти в репозиторий нажать, будет желтый баннер с кнопкой [Compare & pull request] 
добавить описание пулл реквеста > [create pull request] можно добавить описание > [Confirm merge]
```
10. Синхронизировать Внешнюю и Локальную ветки Main
```
git checkout main 
git pull
```
