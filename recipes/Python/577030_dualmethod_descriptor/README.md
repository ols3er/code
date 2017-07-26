## dualmethod descriptor  
Originally published: 2010-02-04 16:06:33  
Last updated: 2010-02-06 20:54:45  
Author: Steven D'Aprano  
  
This descriptor can be used to decorate methods, similar to the built-ins classmethod and staticmethod. It enables the caller to call methods on either the class or an instance, and the first argument passed to the method will be the class or the instance respectively.