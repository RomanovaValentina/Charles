# Charles proxy!
# 
![image](https://habrastorage.org/getpro/habr/upload_files/dc0/8bb/13a/dc08bb13ae279fe88f3391c67b708b2d.png)

Task:
Сделать и в Rewrite, и в BreakPoint 
 ⁃ Подменить url в Charles чтобы в запросе ушло имя которые вы вписали в Postman, а вернулось то, которое вы подставили в Charles.
 ⁃ Подменить body в Charles так чтобы в запросе ушла salary которую вы вписали в Postman, а в u_salary_1_5_year цифра вернулась меньше оригинальной из запроса.
 ⁃ Подменить параметры запроса в Charles так, чтобы в Postman пришел ответ где другое name, daily_food > weight из запроса, а daily_sleep < weight из запроса.
 ⁃ Сделать через Charles так, чтобы сервер вернул 500 код.
 ⁃ Сделать через Charles так, чтобы сервер вернул 405 код.
 ⁃ Сделать через Charles так, чтобы сервер вернул 405 ошибку.
 ⁃ Подменить salary в request
 ⁃ Подменить (salary * 2) в response
  ⁃ Сделать через Charles так, чтобы в Postman вернулся ответ, в котором qa_salary_after_1.5_year переименовано в qa_salary_after_1.5_month
 ⁃ Сделать так чтобы qa_salary_after_3.5_years было меньше qa_salary_after_12_months в response
