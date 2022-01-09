const Discord = require('discord.js');
 const client = A venit pe server .Client();

client.on('ready', () => {
 console.log(`Logged in as ${client.user.tag}!`);
 });

client.on('message', msg => { hey
 if (msg.content === 'ping') {
 msg.reply('pong');
 }
 });

client.login('OTI5ODIzMjUxNjY2OTg5MDk2.Yds7Yg.ACRThPv5H5P-qDuK2NDr84Hocl8');
