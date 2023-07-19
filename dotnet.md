```csharp
private static SecretNames GetConfiguration() => new ConfigurationBuilder()
        .SetBasePath(Directory.GetCurrentDirectory())
        .AddJsonFile("appsettings.Test.json", optional: true)
        .Build()
        .GetSection(SecretNames.SectionName)
        .Get<SecretNames>()!;
```
