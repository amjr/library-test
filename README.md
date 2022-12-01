# Requisitos
  Conta criada no npm
  .npmrc configurado
  .babelrc configurado
  npm.ignore configurado (não obrigatório)
  webpack.config.js configurado
  no package.json --- "repository":{"type":"git","url":"git+https://github.com/amjr/library-test.git"}  (configuração do rep com url do package)
# Publicar
  Para publicar é necessário buildar o porjeto (npm run build)
  após o build, definir uma versão (npm version 0.0.26)
  após a versão definida executar o comando de publicar (publico: npm publish --access public  || privado: npm publish)
  é necessário commitar alterações após o build

# Exemplo de uso (lado consumindo o pacote)
import {Button} from '@amjr/library-test/'


