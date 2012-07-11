Changes in 1.1-hudson-20120704-SNAPSHOT:

- Removed the dependency on Jaxen. XPath and XSLT support is provided by a service
  that allows providers with alternative implementations. The default service is
  capable enough to allow a plugin service provider to be loaded.
  
- Fixed several tests and bugs.

The previous version of commons-jelly was forked for Hudson.
