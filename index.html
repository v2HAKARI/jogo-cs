// Obtém referência para o canvas e seu contexto 2D
const canvas = document.getElementById('gameCanvas');
const ctx = canvas.getContext('2d');

// Definição das variáveis do jogador
let player = {
    x: canvas.width / 2,
    y: canvas.height - 50,
    width: 50,
    height: 50,
    color: '#00FF00',
    speed: 5,
    bullets: []
};

// Controle do jogador usando o teclado
document.addEventListener('keydown', function(event) {
    if (event.key === 'ArrowLeft') {
        player.x -= player.speed;
    } else if (event.key === 'ArrowRight') {
        player.x += player.speed;
    } else if (event.key === ' ') { // Espaço para disparar
        player.bullets.push({
            x: player.x + player.width / 2 - 2.5, // Ajuste para centralizar o tiro
            y: player.y,
            width: 5,
            height: 10,
            color: '#FF0000',
            speed: 10
        });
    }
});

// Função principal de desenho do jogo
function draw() {
    // Limpa o canvas
    ctx.clearRect(0, 0, canvas.width, canvas.height);

    // Desenha o jogador
    ctx.fillStyle = player.color;
    ctx.fillRect(player.x, player.y, player.width, player.height);

    // Desenha os tiros do jogador
    player.bullets.forEach(function(bullet) {
        ctx.fillStyle = bullet.color;
        ctx.fillRect(bullet.x, bullet.y, bullet.width, bullet.height);
        bullet.y -= bullet.speed; // Movimento dos tiros para cima

        // Remove tiros que saíram da tela
        if (bullet.y < 0) {
            player.bullets.splice(player.bullets.indexOf(bullet), 1);
        }
    });

    // Chamada de animação
    requestAnimationFrame(draw);
}

// Inicia o loop do jogo
draw();
