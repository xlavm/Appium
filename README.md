# Appium
Repo for Appium 


```java
    @And("se verifica boton no habilitado")
    public void seVerificaBotonNoHabilitado() {
        if (System.getProperty("platformName").equals("Android")){
            Assert.assertEquals(false,Boolean.parseBoolean(ingresoDatosPage.isNotEnabledBoton()));
        }else{
            Assert.assertEquals(true,Boolean.parseBoolean(ingresoDatosPage.isNotEnabledBoton()));
        }
    }
```