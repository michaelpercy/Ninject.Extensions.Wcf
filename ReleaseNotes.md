Version 3.2.2
---------------
- Fixed: WS-Discovery does not work.

Version 3.2.1
---------------
- Changed: Set ```NinjectBehaviorExtensionElement```'s kernel when start

Version 3.2.0
---------------
- Added: Transient scoped services are disposed when not used anymore.
- Added: Endpoints can now be configured in the app config. Rest service and mex bindings can now be used together with NinjectServiceHostFactory. Marked NinjectWebServiceHostFactory obsolete
- Added: Better support for selfhosting
- Added: #21: Close or abort wcf client depending on its state before dispose
- Added: Support WCF behaviors
- Changed: Transient Services are disposed when not used anymore

Version 3.0.0.0
---------------
- Added: Support for restful services
- Added: Support for data services
- Added: NinjectServiceHost<T> to support creation of self hosted services without having to define ServiceHost bindings
- Added: Support for singleton services hosted on IIS
- Changed: Wcf IIS hosting is now based on Ninject.Web.Common
