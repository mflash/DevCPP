# Imagem base com Java 21 (OpenJDK) e Maven pré-instalados
FROM mcr.microsoft.com/devcontainers/base:trixie

# Atualização de pacotes e instalação do Graphviz, Gnuplot e GCC/G++ em um único layer
RUN apt-get update && \
    apt-get upgrade -y && \
    apt-get install -y graphviz gnuplot g++ && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*



