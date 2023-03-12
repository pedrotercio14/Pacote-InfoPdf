# Pacote-InfoPdf
Pacote Python desenvolvido na disciplina de Programação Orientada a Objetos II, com a funcionalidade de ler e traduzir arquivos em formato Pdf e fazer a conversão traduzida para TXT.

# Instalação

pip install infoPdf

# Uso

from infoPdf import InfoPdf

info = InfoPdf() info.SayThis('certificado.pdf')

info = InfoPdf() info.Translator('certificado.pdf', 1)
