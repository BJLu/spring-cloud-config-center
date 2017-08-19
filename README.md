# spring-cloud-config-center <br>
此仓库存放所有的spring cloud项目的配置文件 <br>
所有配置文件的名称格式如下：<br>
/{application}/{profile}[/{label}] <br>
/{application}-{profile}.yml <br>
/{label}/{application}-{profile}.yml <br>
/{application}-{profile}.properties <br>
/{label}/{application}-{profile}.properties <br>
其中application就是项目名称，profile是环境，如dev/qa/pre/pro等，label是git分支,默认master <br>
详细信息见http://cloud.spring.io/spring-cloud-static/Dalston.SR2/#_spring_cloud_config <br>
