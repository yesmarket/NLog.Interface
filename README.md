NLog.Interface
==============

Defines an abstraction for NLog.Logger public interface that you can use in unit tests and dependency injection.

    ILogger logger = new LoggerAdapter(NLog.LogManager.GetCurrentClassLogger());
	logger.Info("Hello World!");


## License

NLog.Interface is licensed under [MIT License](http://opensource.org/licenses/MIT "Read more about the MIT license form"). Refer to license file for more information.