npm i lerna -D
npx lerna init

// 可以用设置npmClient 使用yarn安装
npm set registry https://registry.npm.taobao.org/


lerna add babel


lerna add babel , 该命令会在package-1和package-2下安装babel  
lerna add react --scope=package-1 ,该命令会在package-1下安装react  
lerna add package-2 --scope=package-1，该命令会在package-1下安装package-2  


