
-  **Comandos**
	Crear un ejecutable EXE
		- Dentro de la carpeta del proyecto:
		  $ dotnet publish -c Release -r win-x64 --self-contained true -p:PublishSingleFile=true -p:IncludeNativeLibrariesForSelfExtract=true -p:DebugType=None 
		  El fichero se crea en el directorio: \bin\Release\netX.X-windows\publish\
		
