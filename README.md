# soapui-demo

Test Git setup


if HTML is not rendered properly in Jenkins use these in Manage jenkins > Script console

System.clearProperty("hudson.model.DirectoryBrowserSupport.CSP");

System.setProperty("hudson.model.DirectoryBrowserSupport.CSP", "sandbox allow-scripts; default-src 'self'; script-src * 'unsafe-eval'; img-src *; style-src * 'unsafe-inline'; font-src *");
