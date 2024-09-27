# WhaTicket Versão 5.0 Saas com Módulo Kanban, Modo Noturno, Google Gemini, e Instagram</br>
Está é uma versão modificada</br>
Desde 23/11/2023 este se tornou um diretório aberto, para uso livre.

Funcionando com a última versão do Baileys 6.6.3 - Setembro de 2024</br>

Apesar de ter os botões de conexões de insta e messenger, agora a do instagram está funcionando, bastando criar o app no Meta Developer

Notas Rápidas: </br>
Requer servidor Ubuntu 20.04 LTS com ao menos 4vcore e 8gb de ram.</br>

Funciona perfeitamente na Hostinger



Utilize este instalador:

```
https://github.com/its-tecnologias/w/instalador.git
```

Siga o arquivo de intruções deste repositório para instalação e fix da biblioteca e do nginx.
Confira no pdf aqui como gerar um webhook de retorno de pagamento do Efi.

Bugs Relatados:</br>
O sistema configurado 100% não tem apresentados bugs. 
</br>Exceção a instalações onde a uma discrepâncias de latência entre a instalação e os servidor de whatsapp, </br>então não funciona em localhost ou servidor local, com ping muito baixo.

Personalizações:</br>

** Alterar Cor Primária: (#007aff)</br>
```
/frontend/src/config.json</br>
/frontend/src/App.js</br>
/frontend/src/layout/index.js</br>
/frontend\src\pages\Chat\ChatMessages.js
```

** Cores do Chat Interno:</br>
```
frontend\src\pages\Chat\ChatList.js</br>
```

** Cores da Lista de Tarefas</br>
```
/frontend/src/pages/ToDoList/index.js
```

** Popover de Anúncios / Chat Interno </br>
```
/frontend/src/components/AnnouncementsPopover/index.js</br>
/frontend/src/pages/Chat/ChatPopover.js
```

** Logo e LogoLogin:</br>
```
/frontend/src/assets
```

** Icone e Favicon:</br>
```
/frontend/public
```

** Comando para rebuild, caminho absoluto /home/deploy/"nome"/</br>
Sempre que fizer alguma alteração nos arquivos é necessário rebuildar a aplicação.
  
```
cd /frontend
npm run build
```

URL WEBHOOK META:

```bash
https://api.seudominio.com.br/webhook/fb
```
