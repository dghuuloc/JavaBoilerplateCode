# <p align="center">Java Boilerplate Code</p>
---

## How to create Java project base on Java Boilerplate Code

### Clone Java Boilerplate Code to `C:\Users\<UserName>\jdtls-workspace`
```
https://github.com/dghuuloc/JavaBoilerplateCode.git <ProjectName>
```
Change <ProjectName> with your expected Name. For Example:

```
https://github.com/dghuuloc/JavaBoilerplateCode.git JavaCore
```
### Remove `.git`
```
rm -rf .git
```

### Edit `.project` file
```
<?xml version="1.0" encoding="UTF-8"?>
<projectDescription>
	<name>ProjectName</name>
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
	<linkedResources>
		<link>
			<name>_</name>
			<type>2</type>
			<location>C:/Users/UserName/jdtls-workspace/JavaBoilerplateCode</location>
		</link>
	</linkedResources>
	<filteredResources>
		<filter>
			<id>1730818492617</id>
			<name></name>
			<type>30</type>
			<matcher>
				<id>org.eclipse.core.resources.regexFilterMatcher</id>
				<arguments>node_modules|\.git|__CREATED_BY_JAVA_LANGUAGE_SERVER__</arguments>
			</matcher>
		</filter>
	</filteredResources>
</projectDescription>
```
