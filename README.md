# TER_v.4.5.1

      </dependentAssembly>
    </assemblyBinding>
      <gcConcurrent enabled="true" /> 
      <gcServer enabled="true" /> 
  </runtime>
  <startup>
    <supportedRuntime version="v4.0" sku=".NETFramework,Version=v4.6.2" />
    <supportedRuntime version="v4.0" sku=".NETFramework,Version=v4.8" />
  </startup>
  <nlog autoReload="true" xmlns="http://www.nlog-project.org/schemas/NLog.xsd" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
    <variable name="logDirectory" value="${basedir}/Logs/${shortdate}" />
