
# spring study

```java
	@Autowired
	private TestMapper testMapper;
	
	public String test() {
		Integer ret = testMapper.select1();
		return Integer.toString(ret);
	}
```

annotation