# 1. NAVEGUE ATÉ O DIRETÓRIO ONDE VOCÊ QUER SALVAR O ARQUIVO (Exemplo: pasta Downloads)
cd ~/Downloads

# 2. BAIXE O ARQUIVO KODI APPIMAGE
# IMPORTANTE: Você deve ATUALIZAR a URL abaixo [LINK_DE_DOWNLOAD_AQUI] com o link direto do seu Kodi-x86_64.AppImage
wget -O Kodi-x86_64.AppImage [LINK_DE_DOWNLOAD_AQUI]

# 3. CONCEDA PERMISSÃO DE EXECUÇÃO
# O comando chmod torna o arquivo executável para o usuário
chmod u+x Kodi-x86_64.AppImage

# 4. INICIE O KODI
# O comando ./ executa o AppImage
./Kodi-x86_64.AppImage
