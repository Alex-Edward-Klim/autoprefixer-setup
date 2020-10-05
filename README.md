npm i -D
autoprefixer
postcss
postcss-loader

postcss.config.js
module.exports = {
  plugins: [
    require('autoprefixer')
  ]
}

webpack.config.js
"postcss-loader"

package.json
"browserslist": [
    "> 0%"
  ],
