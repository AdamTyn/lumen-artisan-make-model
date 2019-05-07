# lumen-artisan-make-model
移植Laravel的 `php artisan make:model` [快速创建模型] 指令到Lumen

# Usage
在 **'app/commands/kernel.php'** 中注册指令：
```  

protected $commands = [
	\AdamTyn\Lumen\Artisan\ModelMakeCommand::class
];
```
