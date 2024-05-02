<h1 align="center"> Básico de internet. </h1>


<h2> internet </h2>
<h3> O papel dos protocolos na Internet </h3>

Um protocolo é um conjunto de regras e padrões que definem como as informações são trocadas entre dispositivos e sistemas. A internet é um grupo de computadores e outros diversos dispositivos conectados uns aos outros. Para ter a comunicação entre essses diversos dispositivos são utilizados diversos protocolos, entre eles estão os seguintes:
<ul>
  <li> Protocolo IP (Internet Protocol): Cada dispositivo contem um único numero IP, representados como uma série de quatro números separados por pontos, como “192.168.1.1”. Sendo ele o responsável por rotear pacotes de dados para o seu destino correto.</li>
  <br>
  <li> Protocolo TCP (Trnsmission Control Protocol): Garante que o roteamento dos pactes de dados do feito pelo protocolo IP sejam transmitidos de maneira confiável e eficiente..</li> 
  <br>
  <li> Alguns conceitos para construção de aplicativos com TCP/IP:</li>
  
  - Portas: usada para identificar o serviço ou o aplicativo que está em execução, o aplicativo ou o serviço em execução vai ter um número de porta único.
    
  - Sockets: combinação do número de IP e um número de porta.
    
  - Connections: estabelecida entre dois Sockets quando dois dispositivos precisam se comunicar. Havendo uma negociação de parâmetros, como o tamanho máximo do segmento e da janela, e determina como os dados serão transmitidos pela conexão.
    
  - Data transfer: transmitidos em segmentos contendo um número de sequência e outros metadados que garatem o recebimento e envio dos dados.
  
  - Protocol DNS (Domain Name System): Faz a tradução dos nomes de dominios em endereços IP.
  
  - HTTP e HTTPS: protocolo usado para transferir dados entre um cliente (como um navegador da web) e um servidor (como um site). HTTPS é a versão mais segura, ela faz a transmissão dos dados para os clientes usando a criptografia SSL/TSL (Secure Sockets Layer/Transport Layer Security).
  <br>
  
  <li>SSL/TLS: protocolos de criptografia usados para garantir a segurança de comunicação pela internet.</li>
  <br>
  
  - Alguns conceitos sobre SSL/TLS:

  - Certificados: usados para estabelecer uma uma comunicação confiável entre clientes e servidores, contém informações sobre os servidores que são garantidas por um terceiro que possui a autoridade para tal.

  - Handshake: é a troca de informações realizadas pelo cliente e o servidor sobre a criptografia de algoritmose outros parâmetros.
    
  - Encriptação: quando a conexão é estabelecida os dados são encriptados usado o que foi acordado.
  <br>
  
  <li> Domain Names: "google.com" é um nome de domínio que será traduzido usando o DNS. Após seu dispositivo fazer uma requisição de DNS para o servidor DNS, que vai retornar um IP corresponde ao site que foi digitado pelo cliente.</li>
  
  - Conceitos:
    
  - Qualquer computador conectado à Internet pode ser acessado através de um endereço IP público, seja um endereço IPv4 (por exemplo 192.0.2.172) ou um endereço IPv6 (por exemplo, 2001:db8:8b73:0000:0000:8a2e:0370:1337).
    
  - Estrutura: estrutura simples composta por várias partes (pode ser uma parte apenas, duas, três…), separadas por pontos e lidas da direita para a esquerda:
  <br>
  
 <img> ![structure](https://github.com/Dev-Duardo/backend_development_roadmap/assets/86846534/11480467-7aa0-4bba-91e4-e46a7ae2335a) </img>
  
  <br>
  
  - TLDS locais: TLDs locais como .us, .fr, ou .sepodem exigir que o serviço seja fornecido em um determinado idioma ou hospedado em um determinado país. os que contêm .gov só podem ser usados ​​por departamentos governamentais. O .edu TLD deve ser usado apenas por instituições educacionais e acadêmicas. comprimento máximo de um TLD é de 63 caracteres, embora a maioria tenha cerca de 2–3.

</ul>

