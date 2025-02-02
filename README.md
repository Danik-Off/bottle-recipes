# Bottle Recipes  

`bottle-recipes` — коллекция скриптов для создания префиксов (**бутылок**) в **Bottles**, организованных по папкам с названиями программ.  

## Структура  
Каждая папка соответствует определённому приложению и содержит скрипты для создания и настройки его префикса.  

### Пример:  
```  
bottle-recipes/  
│── ms-office/  
│   ├── office16.sh
|   ├── office16.md

```  

## Использование  
1. Перейдите в папку нужного приложения:  
   ```sh  
   cd bottle-recipes/ms-office  
   ```  
2. Запустите скрипт:  
   ```sh  
   bash create.sh  
   ```  

## Требования  
- **Bottles** (установленный и настроенный)  
- **bash** (или совместимый интерпретатор)  

## Лицензия  
Этот проект распространяется под лицензией **MIT**.
