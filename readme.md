# SASS Atomic Vars based on Open Props 

This is a project to help extend SASS projects using the open props 
themeing and style system. 

General usage: 

```@use 'atomic-vars/loader' as _a; 

$brand-0 #{_a.$color-blue-0}; 
```

The same concepts apply throughout the varriables and match all the open 
props naming conventions for a seamless transition. 

### Shadows: 

```
.inner-shadow-1 { 

	box-shadow: _a.shadow('inner-1', 1);
}
```

Explore the variables and feel free to contribute to the docs.
