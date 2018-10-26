# nuget

* [Include files in Nuget in csprj](https://stackoverflow.com/questions/51217832/including-unmanaged-dll-in-nuget-package-using-csproj)
<pre>
<ItemGroup>
  <None Include="unmanaged.dll" Pack="true" PackagePath="runtimes\win-x64\native" />
</ItemGroup>
</pre>
