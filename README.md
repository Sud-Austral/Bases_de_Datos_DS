# Bases_de_Datos_DS

1 Los decimales en los excels deben ser con comas y guardarse en archivos CSV (MS-DOS) para que 
las columnas se separen con ; y puedan ser leidas con facilidad en PowerBI

2 Se debe comentar: #options("encoding" = "UTF-8") en el codigo R. El resultado crudo del csv 
en R queda mal configurado pero se leera bien en Excel.

# Carga automatica en GitHub

install.packages("git2r")
library(git2r)

FileConnection <- file("GitHub.R")

writeLines( paste0("#This is a test script. Run at: ", format(Sys.time(), "%Y-%m-%d %H:%M:%S"))

          , FileConnection
          
          )
          
close(FileConnection)

rm(FileConnection)

Pull the Repo again

pull( repo = getwd()

    , credentials = cred_user_pass( username = "YourUserName" 
    
                                  , password = "YourPassord"  
                                  
                                  )                           
    )


<!---
https://rpubs.com/chrimaho/GitHubAutomation
% ![](mongodb.png)
-->
http://estadistica.ssmso.cl/demografia-y-estadisticas-por-tema/

https://www.bcn.cl/siit/estadisticasterritoriales/

Tasas a nivel de Comuna - Centro de Estudios MINEDUC
centroestudios.mineduc.cl › uploads › sites › 2018/08 › 2...
XLS
10 ago. 2018 - Anuario de Estadisticas Vitales 2012 INE, tasas de mortalidad por ... las tasa de deserción del sistema global, por curso, región, comuna y dependencia. ... 46, PROVINCIA ANTARTICA CHILENA, 13, 428, 3.0%, 13, 428, 3.0% ...

Estimaciones de Tasa de Pobreza por Ingresos y Multidimensional por Comunas, 2017

http://observatorio.ministeriodesarrollosocial.gob.cl/indicadores/datos_pobreza_comunal.php




