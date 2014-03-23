SQL Script runner
=================

Loading example:
```Java
Connection connection = YOUR CONNECTION TO DATABASE;
SqlScriptRunner script = new SqlScriptRunner(connection,true,true);
FileReader createTables = new FileReader("path/to/your/script/file");
script.runScript(createTables);
```
