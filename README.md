<h1>Configuração do Maestro no Windows</h1>

> Um guia passo a passo para instalar o Maestro no Windows

<p>O Maestro Mobile é uma ferramenta poderosa para teste de aplicativos mobile em plataformas Android e iOS, e funciona excepcionalmente bem em computadores, Windows. No entanto, a configuração no Windows requer algumas etapas específicas que precisam ser seguidas para garantir o funcionamento correto do software. Este guia técnico detalhado irá orientá-lo por todas as etapas necessárias, desde a instalação até a configuração final, para que você possa começar a usar o Maestro Mobile em sua máquina Windows de maneira eficiente.</p>

<h2>Pré-Requisitos</h2>

<ol>
  <li>O PowerShell está instalado no seu sistema Windows.</li>
  <li>Instale o Android Studio em sua máquina Windows.</li>
      <ol>
        <li>Baixe o Android Studio acessando o link https://developer.android.com/studio?hl=pt-br</li>
        <li>Aceite os termos de compromisso para inicializar o download</li>   
        <br />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/37d0b133-9952-4a77-be92-b3f35228c613" alt="Aceita os termos para baixar o Android Studio" height=500>
        <br />
        <hr />
        <li>Ter a permissão para a a instalação do Android Studio</li>
        <br />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/71e1989f-aa4d-42f6-baf7-c737304c913b" alt="permissão para instalação do Android Studi" height=500 />
        <br />
        <hr />
        <li>Nas próximas etapas é só clicar em <strong>next</strong> como nas imagens abaixo</li>
        <br />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/4bc254c7-26e4-42d7-9ea7-aa9ce6db6caa" alt="Etapas de configuração de instalação do Android Studio" height=500 />
        <br />
        <hr />       
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/8aba97b3-3278-44ad-aca5-7e6e035966e2" alt="Etapas de configuração de instalação do Android Studio" height=500 />
        <br />
        <hr />        
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/4fc2111f-9d8b-4a12-9d15-367b04ff8c14" alt="Etapas de configuração de instalação do Android Studio" height=500 />
        <br />
        <hr />
        <li>Agora clicar em <strong>Install</strong> para realizar a instalação do Android Studio</li>
        <br />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/8e9f5463-f9be-45dc-a0d2-e6e4f1532fef" alt="Instalação do Android Studio" height=500 />
        <br />
        <hr />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/48bcc01b-ec99-4529-9915-b746ecfac40e" alt="Instalação do Android Studio" height=500 />
        <br />
        <hr />
        <li>Instalação completa, clicar em <strong>Next</strong></li>
        <br />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/30a2f288-530f-47a3-9746-02b8754e804d" alt="Instalação completa do Android Studio" height=500 />
        <br />
        <hr />
        <li>Finalizar a instalação e inicializar o Android Studio para realizar configurações</li>
        <br />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/35bf75b2-e562-49fc-bc3d-149f951e7ee6" alt="Finalizar instalação e inicializar o Android Studio" height=500 />
        <br />
        <hr />
        <li>Como provalmente deverá ser a primeira instalação, ou se não quiser importar alguma configuração anterior, basta marcar a opção como na imagem abaixo</li>
        <br />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/4533bbe6-ec89-4183-bba0-ac47d0707516" alt="Configuração do Android Studio" height=500 />
        <br />
        <hr />
        <li>No próximos passo só clicar em <strong>Next</strong> como nas imagens abaixo</li>
        <br />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/8863f629-77e4-40b5-a172-c1fce99f3908" alt="Configuração do Android Studio" height=500 />
        <br />
        <hr />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/57755ed9-912e-4ff3-bf15-f8b6f9fb861f" alt="Configuração do Android Studio" height=500 />
        <br />
        <hr />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/5b2246c5-5f01-4132-97e8-2dcd20185fee" alt="Configuração do Android Studio" height=500 />
        <br />
        <hr />
        <li>Aceite as licenças</li> 
        <br />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/f7ec16c6-498a-4222-83f4-d8e1c862634b" alt="Permissões do Android Studio" height=500 />
        <br />
        <br />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/faa9833f-0362-460a-85fb-4988026b7abb" alt="Continuação das configurações de instalação do Android Studio" height=500 />
        <br />
        <br />
        <li>Finalizar a instalação do Android Studio</li>
        <br />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/8669d070-7bc7-449e-85ab-acef803e5884" alt="Finalização da instalação do Android Studio" height=500 />
        <br />
        <hr />
        <li>Criar um emulador virtual</li>
        <br />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/429b53f3-72f8-47b6-870d-6a3c076798b7" alt="Criar um emulador virtual" height=500 />
        <br />
        <hr />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/cd9f068e-10c9-4a73-bced-ebd5f14feb99" alt="Criar um emulador virtual" height=500 />
        <br />
        <hr />
        <li>Por padrão a instalação do Android Studio já criar um emulador virtual</li>
        <br />
        <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/ac586b6a-bfd7-4cc4-9a8b-4f0149641937" alt="Emulador virtual do Android" height=500 />   
      </ol>
    <li>Adicione ANDROID_HOME à sua variável de ambiente do Windows.</li>
        Geralmente estará em <code>C:\Users\<strong>SEU USUÁRIO</strong>\AppData\Local\Android\Sdk</code>
        <br />
        <br />
        <blockquote>A pasta AppData é uma pasta oculta necessário liberar sua visualização</blockquote>
        <br />
        <br />
        <ol>
          <li>Cópia o caminho da pasta <code>Android/Sdk</code></li>
          <li>Acessa as configurações de Variáveis de Ambiente do Windows</li>
          <br />
          <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/19bc5daf-a43b-4de1-a599-ef902fe42110" alt="Editar variáveis de ambiente do Windows" height=400 /> 
          <br />
          <hr />
          <li>Em Variáveis do sistema clicar em <strong>Novo</strong></li>
          <br />
          <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/3a3a7180-d576-4818-ae84-54856087c8fe" alt="Variáveis do ambiente" height=400 />
          <br />
          <hr />
          <li>Em <strong>Nome da variável</strong> colocar <strong>ANDROID_HOME</strong> e no <strong>Valoda da variável</strong> o caminho</li>
          <br />
          <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/5040fe2b-de30-4d8f-84d4-6a7b8ca6b585" alt="Criar variável de Ambiente do ANDROID_HOME" height=400 />
          <br />
          <hr />
          <li>Depois só clicar em <strong>OK</strong> até fechar as janelas</li>  
          <br />
          <li>Para verificar se sua configuração do ANDROID_HOME está feita corretamente, abra um terminal do PowerShell e execute os comandos: <code>echo %ANDROID_HOME%</code> e <code>adb --version</code></li>
          <br />
          <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/1b1b7d25-a789-4dbc-b74d-32823b262755" alt="Verificar a variável de ambiente do ANDROID_HOME" height=400 />
        </ol>
  <li>Instale o Java JDK e defina <strong>JAVA_HOME</strong> nesse caso está sendo instalado o JDK 17</li>
    <ol>
      <li>Acessa a página da Oracle https://www.oracle.com/java/technologies/downloads/#jdk17-windows</li>
      <br />
      <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/49b4c3c5-07bf-4ad6-90ea-d240f91c3279" alt="Baixar o JDK de acordo com a configuração da BIOS do computador" height=500 />
      <br />
      <hr />
      <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/8f99f3a2-0813-4b72-a66b-fc1610324ec1" alt="Aceita os termos" height=200 />
      <br />
      <hr />
      <li>No próximos passo basta clicar em <strong>Next</strong></li>
      <br />
      <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/ec3a0bec-8c57-4ffa-b61a-89520606fa67" alt="Instalação do JDK" height=400 />
      <br />
      <hr />
      <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/6fb6c10c-4f32-4195-a5e9-49b9e01ae0a1" alt="Instalação do JDK" height=400 />
      <br />
      <hr />
      <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/847161db-4463-41c4-981d-8baa7f5e839f" alt="Instalação do JDK" height=400 />
      <br />
      <hr />
      <li>Por fim clicar em <strong>close</strong></li>
      <br />
      <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/ef9ca382-dd63-42ee-9c59-499d2a3b8a04" alt="Instalação do JDK" height=400 />
      <br />
      <hr />
      <li>Acessa a pasta de instalação do Java é cópia o caminha da pasta para configurar a variável de ambiente do Java</li>
      <br />
      <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/7a89e75f-26c5-4042-bc8a-f2906395a47a" alt="Pasta de instalação do Java" height=400 />
      <br />
      <hr />
      <li>Assim como nas configurações do variável de ambiente do <strong>ANDROID_HOME</strong> acessar as configurações de variáveis e criar a variável <strong>JAVA_HOME</strong></li>
      <br />
      <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/db13b1ba-472a-4e81-b691-c6133384b513" alt="Criação da variável de ambiente JAVA_HOME" height=400 />
      <br />
      <hr />
      <li>Para verificar se o Java está instalado corretamente   <code>java --version</code></li>
      <br />
      <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/ede6a425-f37d-4aa7-95b6-f1d56c8fbb9f" alt="Verificação da variável de ambiente JAVA_HOME" height=400 />
      <br />
    </ol>
  <li>Por fim ainda nas váriaves de ambiente apontar o caminho das variáveis do <strong>ANDROD_HOME/platform-tools</strong> e também <strong>JAVA_HOME/bin</strong> como na imagem abaixo</li>
  <br />
  <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/c758d6ce-f8d5-49cb-a5b9-0219e15c4296" alt="Configuração geral das variáveis de ambiente" height=400 />
  <br />
  <hr />
  <img src="https://github.com/CristianoSFMothe/maestro/assets/68359459/40686662-cfdc-469f-ad64-d7e7643ef0c5" alt="Configuração geral das variáveis de ambiente" height=400 />
</ol>


   
