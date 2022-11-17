/**
   * Create By Dika Ardnt.
   * Recode By Naze Dev && Papah-Chan
   * Contact Me on wa.me/6282287219167
   * Follow https://github.com/FahriAdison
*/

const fs = require('fs')
const chalk = require('chalk')

// Website Api
global.APIs = {
	zenz: 'https://zenzapis.xyz',
}

// Apikey Website Api
global.APIKeys = {
	'https://zenzapis.xyz': '0e92565522',
}

// Other
global.owner = ['6285697285563']
global.ownernomer = "6285697285563"
global.premium = ['6285697285563']
global.packname = 'TIMZZBOT'
global.author = '@nyour_tim'
global.sessionName = 'papah'  //jangan diganti bro nanti error
global.jumlha = '999'
global.jumhal = '100000000000000'
global.jumlah = '1000000000'
global.prefa = ['','!','.','#','&']
global.sp = ''

// Setting Mess
global.mess = {
    success: 'Selesai',
    admin: 'Perintah ini hanya bisa digunakan untuk admin group!',
    botAdmin: 'Jadikan Bot sebagai admin terlebih dahulu!',
    premime: 'Perintah ini khusus member premium, kalo mau daftar ketik sewa / chat owner',
    owner: 'Perintah ini hanya bisa digunakan oleh owner',
    group: 'Perintah ini hanya bisa digunakan di group!',
    private: 'Perintah ini hanya bisa digunakan di private message!',
    bot: 'Fitur khusus pengguna nomor Bot',
    wait: 'Loading...',
    error: 'Error!',
    errapi: 'Error, mungkin APikey tidak valid!',
    errmor: 'Error, Kesalahan Sistem',
    endLimit: 'Limit harian anda telah habis, Limit akan direset setiap jam 12',
}

// Limit
global.limitawal = {
    premium: "Infinity",
    free: 25
}

// Fake
global.thumb = fs.readFileSync('./media/image/papah.jpg')
global.faall = fs.readFileSync('./media/image/menu.jpg')

// Url
global.mygit = 'https://github.com/gwxyz'
global.myyt = 'https://bit.ly/Papah-Chan'
global.myytv = ''
global.mygc = ""

// Engak Ngaruh, Belum Kepasang
global.botname = 'TIMZZ BOT'
global.akulaku = 'Bot By TimzzDev'
global.ytname = 'YT PAPAH' //Kalo Ngk Punya Yt Ngak Usah Di Ganti


let file = require.resolve(__filename)
fs.watchFile(file, () => {
	fs.unwatchFile(file)
	console.log(chalk.redBright(`Update'${__filename}'`))
	delete require.cache[file]
	require(file)
})
