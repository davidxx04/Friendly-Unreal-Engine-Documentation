I will list the macros that I find incredibly important.

## UPROPERTY
Define a variable and add functionality like doing it visible in the UE editor details panel...
Here are the param options that you can choose:
#### 1. First param
	- VisibleAnywhere
	- EditAnywhere (makes it visible and editable)
#### 2. Second param
	- BlueprintReadOnly
	- BlueprintReadWrite
#### 3. Third param
	- Category = ...
	- 


## UFUNCTION
Define a function and add functionality like do it a blueprints block function...
#### 1. First param
	- BlueprintCallable -> To call the function in blueprint (as a blueprint block)
	- BlueprintNativeEvent -> Rewrite a native UE function with the one with this param
	- BlueprintImplementableEvent -> You only declare it to implement it in blueprint
#### 2. Second param
	- BlueprintReadOnly
	- BlueprintReadWrite
#### 3. Third param
	- Category = ...
	- 