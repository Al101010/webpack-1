Сделал Fork:
https://github.com/Al101010/ajs-homeworks.git
потом у себя в "Git Bach Here": git clone https://github.com/Al101010/ajs-homeworks.git

Скопировал папку ci-template в C:\_GitHub_\Module_WebPack и переименовал WebPack-1

создал репозиторий webpack-1 клонировал себе C:\_GitHub_\Module_WebPack\
содержимое папки ci-template скопировал в C:\_GitHub_\Module_WebPack\webpack-1

в PS C:\_GitHub_\Module_WebPack\webpack-1> 
npm install




npm install --save-dev mini-css-extract-plugin css-loader

добавил в файл webpack.config.js строку: 
	const MiniCSSExtractPlugin = require('mini-css-extract-plugin');
и
	MiniCSSExtractPlugin.loader,
и
        test: /\.css$/i,
        use: [
            MiniCSSExtractPlugin.loader,
            'css-loader'
        ]

в "Git Bach Here": 
git add .
git commit -m "first commit webpack"
git push
