# lumen-artisan-serve
移植Laravel的快速启动服务的Artisan指令到Lumen

# Usage
在 **'app/commands/kernel.php'** 中注册指令：
```  

protected $commands = [
	\AdamTyn\Lumen\Artisan::class
];
```
