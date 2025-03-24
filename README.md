# blooket-hack
No es toy segura de que fusion ne
blooket-hack
(async () => {
    let tokens = 500; // Cambia este número para obtener más o menos monedas
    const response = await fetch("https://api.blooket.com/api/users/addtokens", {
        method: "PUT",
        headers: {
            "Content-Type": "application/json",
            "Authorization": localStorage.token // Obtiene tu token de sesión
        },
        body: JSON.stringify({
            name: JSON.parse(atob(localStorage.token.split(".")[1])).name,
            addedTokens: tokens
        })
    });)

    if (response.ok) {
        alert(`¡Has recibido ${tokens} monedas!`);
    } else {
        alert("Error al añadir monedas. Puede que esto ya no funcione.");
    }
})();
git clone https://github.com/tu-usuario/blooket-hack.git
cd blooket-hack
echo "// Código del hack" > blooket-hack.js
git add .
git commit -m "Primer commit del hack de Blooket"
git push origin main
