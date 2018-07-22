# cordova-plugin-chartboost

plugman create --name CordovaPluginChartboost --plugin_id com.unitedcommand.cordova.plugin.chartboost --plugin_version 1.0.0

cd CordovaPluginChartboost

plugman platform add --platform_name ios

plugman platform add --platform_name android

plugman createpackagejson .


# install

cordova plugin add https://github.com/acheo/cordova-plugin-chartboost.git