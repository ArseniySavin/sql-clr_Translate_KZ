This app can help to translate kazakh words on latin. this Build may used in MSSQLServer and C# code.

How use:

Use as SQL function: 1.1. Publish project on your SQLServer. 1.2. Check installed assembly. 1.3. You can call function set @Variable = dbo.TranslateOnCyrillicQazaq('SomeKazakhText') select @Variable

Use as methods C# 2.1. Add reference on assembly. 2.2. Call static class InitializationDictionary var exString = InitializationDictionary.ConvertTo("SomeKazakhText", EnumTransliteType, EnumDirectionType);
