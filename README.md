<img src="https://static.wixstatic.com/media/710ee0_458f30ddbbac4f5993de4d414a957f44~mv2.png/v1/fill/w_55,h_48,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/Logo2_fw.png" height=10% width=10%>

# Fedora 38 para Windows Subsystem for Linux (WSL)

Este projeto tem como objetivo disponibilizar o Fedora para o no Windows via WSL de forma gratuita

Desenvolvido por um amante de Linux e Fedora :)

**O Fedora para WSL não é endossado pelo Fedora Project ou Red Hat, Inc.**

## Instalação

1. Baixe do repositório o arquivo fedora-wsl.tar.gz para o seu Windows.
https://mega.nz/file/k6EnGASZ#KprdEobN9d_tOw61mmKu12qsiRD0xG0eJkjA5F_WGLI

2. Abra o Prompt de Comando ou PowerShell no Windows:

Pressione `Win + R`, digite cmd e pressione `Enter` para abrir o Prompt de Comando. Alternativamente, você pode abrir o `PowerShell` pressionando `Win + X` e selecionando `"Windows PowerShell"`.

3. Importar a distribuição:

Agora, você pode usar o comando `wsl --import` para importar a distribuição Fedora para o WSL. O comando tem a seguinte sintaxe:

`wsl --import NomeDaDistro PastaDeDestino ArquivoTarGz`

    - NomeDaDistro: O nome que você deseja dar para a sua distribuição no WSL.
    - PastaDeDestino: O local onde os arquivos da distribuição serão armazenados.
    - ArquivoTarGz: O caminho para o arquivo .tar.gz que você criou.

Por exemplo:

`wsl --import FedoraWSL C:\WSL\Fedora C:\Users\SEU_USUARIO\Documentos\fedora-wsl.tar.gz`

Isso importará a distribuição Fedora para o WSL e a armazenará na pasta `C:\WSL\Fedora`.

4. Inicie a distribuição:

Depois de importar a distribuição, você pode iniciá-la usando o comando:

`wsl -d FedoraWSL`

### Documentação geral sobre WSL e Fedora:

- [Instalar Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
- [Documentação do Usuário do Fedora 38](https://docs.fedoraproject.org/en-US/fedora/f38/)
- [Fedora Project Wiki](https://fedoraproject.org/wiki/Fedora_Project_Wiki)
- [Fedora Project IRC](https://fedoraproject.org/wiki/IRC)
- [Pesquisa de Pacotes Fedora](https://apps.fedoraproject.org/packages/)
- [DNF](https://fedoraproject.org/wiki/DNF) (Gerenciador de pacotes do Fedora)

### Suporte e solução de problemas:

1. [Solução básica de problemas](https://docs.microsoft.com/en-us/windows/wsl/troubleshooting) resolverá muitos problemas encontrados com o WSL.
2. Você pode pesquisar seu problema na página principal de [problemas do WSL](https://github.com/Microsoft/WSL/issues).

### Fedora Project

- [Obter Fedora](https://getfedora.org/)
- [Missão e Fundações do Fedora](https://docs.fedoraproject.org/en-US/project/)
- [Fedora Magazine](https://fedoramagazine.org/)
- Twitter: [@fedora](https://twitter.com/fedora)
- [Planet Fedora](http://fedoraplanet.org/)
- [Fedora (Wikipedia)](https://en.wikipedia.org/wiki/Fedora_(operating_system))
