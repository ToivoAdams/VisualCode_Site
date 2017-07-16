### VisualCode
VisualCode is a developer tool which help to visually compose java code.

Tool converts Java methods to visual blocks which can have multiple input and multiple output ports.
Using Visual Flow editor you connect blocks output and input ports.
Resulting visual flow will be converted to executable Java method.
Resulting method is like any other java method and can be called from ordinary java code.

#### Creating blocks

Let's create simple block.
We start with java static method.

```
	public static double add(double a, double b) {
		return a + b;
	}
```
![ExampleFlow](/docs/images/Simple1CodeView.png)

Next open java source file with ‘Code View’ and select Visual View tab.
Now you see visual block.

![ExampleFlow](/docs/images/Simple1CodeViewVisual.png)
