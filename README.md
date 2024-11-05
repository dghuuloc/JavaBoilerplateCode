# <p align="center">Java Boilerplate Code</p>
---

## How to create Java project base on Boilerplate Code

### Clone Java Boilerplate Code to `C:\Users\<UserName>\jdtls-workspace`
```
git clone https://github.com/dghuuloc/JavaBoilerplateCode.git <ProjectName>
```
For Example:

```
git clone https://github.com/dghuuloc/JavaBoilerplateCode.git JavaCore
```

### Remove `.git`
```
rm -rf .git
```

### Edit `.project` file
```xml
<?xml version="1.0" encoding="UTF-8"?>
<projectDescription>
	<name>ProjectName</name>            <!--Change ProjectName with your expected name-->
	<comment></comment>
	<projects>
	</projects>
	<buildSpec>
		<buildCommand>
			<name>org.eclipse.jdt.core.javabuilder</name>
			<arguments>
			</arguments>
		</buildCommand>
	</buildSpec>
	<natures>
		<nature>org.eclipse.jdt.core.javanature</nature>
		<nature>org.eclipse.jdt.ls.unmanagedFolderNature</nature>
	</natures>
</projectDescription>
```
