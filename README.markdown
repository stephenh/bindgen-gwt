
A wrapper project for taking [bindgen](http://www.bindgen.org) source and packaging it together as a GWT-compatible jar.

Artifacts are available from the [joist](http://joist.ws) maven [repo](http://repo.joist.ws/org/bindgen/bindgen-gwt/).

To use, put `bindgen-gwt.jar` on your classpath and modify your `app.gwt.xml` to include:

    <inherits name="org.bindgen.Bindgen" />


