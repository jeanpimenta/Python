# Organizador de Arquivos em python

O código em python, identifica vários tipos de extensões -- indicada no código --, cria algumas pastas pré-determinadas no código, e realoca os arquivos em questão para cada pasta. Demais arquivos não especificados, são todos incluídos para a pasta "outros".

txt = ['.txt']

word = ['.docx', '.doc', '.rtf', '.odt']

powerpoint = ['.pptx', '.ppt']

excel = ['.xlsx', '.xls', '.xlsm', '.csv', '.pbix']

imagens = ['.bmp', '.rle', '.dib', '.gif', '.jpg', '.jpeg', '.jpe', '.png']

design = ['.psd', '.edf', '.cdr', '.ai']

video = ['.flv', '.mp4', '.mov', '.mkv', '.avi', '.mpeg', '.rmvb']

audio = ['.mp3', '.wma', '.aac', '.ogg', '.ac3', '.wav']

compactados = ['.zip', '.rar', '.7z']

pdf = ['.pdf', '.djvu']

executaveis = ['.exe', '.msi']

dev = ['.cpp', '.php', '.js', '.css', '.py', '.sql', '.xml', '.htm', '.html', '.cpp', '.java', '.c', '.dart', '.cs', '.vb', '.xhtml']

tex = ['.tex', '.cls', '.sty']

Caso queira mais patas, adicione-a conforme acima (no código), e adicione mais um elif: elif(extensao in [nome da pasta]): cria_move(arquivo, './[nome da pasta]')