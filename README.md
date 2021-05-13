# MKL

[![](https://jitpack.io/v/mrz07/MKL.svg)](https://jitpack.io/#mrz07/MKL)

This is my private library which I continue to maintain when I am in my spare time in Kotlin programs. I have published
it to make it easier to integrate into my projects. Everybody is welcome to contribute

Mustafas Kotlin Library offers extensive possibilities to improve general development, solving everyday problems,
preventing errors and increase productivity.

This is achieved by:

- Extension of many default classes of the kotlin standard library
- Creation of some global variables and methods
- Offering helper classes
- Validators for Data Types
- Requirement Framework to easily check if certain requirements are met (will be implemented in the future)

### Installing

1. Add this in your root build.gradle at the end of repositories:

```gradle
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

2. Add the dependency (Use the tag 'Snapshot' until a stable release is created )

```gradle
	dependencies {
	        implementation 'com.github.mrz07:MKL:-SNAPSHOT'
	}
