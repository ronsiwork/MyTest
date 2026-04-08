# Build dell'immagine
docker build -t my-node-server .

# Avvio del container
docker run -p 3000:3000 my-node-server
