<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/png" href="image/phinma.png">
    <title>Musify</title>
    <link rel="stylesheet" href="MusicPlaylist.css">
</head>
<body>
    <video autoplay loop muted plays-inline class="backgroundv">
        <source src="image/video.mp4" type="video/mp4">
    </video>
    <div class="header">
        <span>Musify</span>
        <div class="right-section">
            <span><img class="notif" src="image/notification.png"> Notifications</span>
            <span><img class="About" src="image/about us.png"> About Us</span>
            <a href="MusicLogin.html" style="color: white; text-decoration: none;"><span><img class="Account" src="image/account.png"> Account</span></a>
        </div>
    </div>
    <div class="sidebar">
        <div class="itemss">
            <img class="icon" class="active" src="image/home.png">
            <div class="texts" class="active">Home</div>
        </div>
        <div class="itemss">
            <a href="MusicPlaylists.html" style="color: white; text-decoration: none;"><img class="icon" src="image/playlists.png"></a>
            <a href="MusicPlaylists.html" style="color: white; text-decoration: none;"><div class="texts">Playlists</div></a>
        </div>
        <div class="itemss">
            <a href="MusicFavorites.html" style="color: white; text-decoration: none;"><img class="icon" src="image/favorites.png"></a>
            <a href="MusicFavorites.html" style="color: white; text-decoration: none;"><div class="texts">Favorites</div></a>
        </div>
        <div class="itemss">
            <a href="MusicNowPlaying.html" style="color: white; text-decoration: none;"><img class="icon" src="image/now playing.png"></a>
            <a href="MusicNowPlaying.html" style="color: white; text-decoration: none;"><div class="texts">Now Playing</div></a>
        </div>
        <div class="itemss">
            <a href="MusicRecentlyPlayed.html" style="color: white; text-decoration: none;"><img class="icon" src="image/recently played.png"></a>
            <a href="MusicRecentlyPlayed.html" style="color: white; text-decoration: none;"><div class="texts">Recently Played</div></a>
        </div>
        <div class="itemss">
            <img class="icon" src="image/settings.png">
            <div class="texts">Settings</div>
        </div>
        <div class="itemss">
            <a href="MusicLogin.html" style="color: white; text-decoration: none;"></a><img class="icon" src="image/logout.png"></a>
            <a href="MusicLogin.html" style="color: white; text-decoration: none;"><div class="texts">Logout</div></a>
        </div>
    </div>
    <div class="main-home">
        <img class="musify" src="image/musify.png">
        <img class="musify-logo" src="image/musify-logo.png">
        <input class="home-search" type="text" placeholder="Search">
    </div>
    <div class="category-side">
        <div class="category">Category</div>
            <div class="category-box">
                <img src="image/music.jpg">
                <p>POP</p>
            </div>
            <div class="category-box">
                <img src="image/music.jpg">
                <p>ROCK</p>
            </div>
            <div class="category-box">
                <img src="image/music.jpg">
                <p>HIP-HOP / RAP</p>
            </div>
            <div class="category-box">
                <img src="image/music.jpg">
                <p>R&B (RHYTHM & BLUES) / SOUL</p>
            </div>
            <div class="category-box">
                <img src="image/music.jpg">
                <p>COUNTRY</p>
            </div>
            <div class="category-box">
                <img src="image/music.jpg">
                <p>REGGAE</p>
            </div>
            <div class="category-box">
                <img src="image/music.jpg">
                <p>METAL</p>
            </div>
            <div class="category-box">
                <img src="image/music.jpg">
                <p>CLASSICAL</p>
            </div>
    </div>
    <div class="carousel">
        <div class="Popular-Artist">Popular Artist</div>
        <div class="wrap">
            <div class="slide">
                <img src="image/music.jpg" alt="">
                <p class="caption">artist name</p>
                <p class="caption1">Artist</p>
            </div>
            <div class="slide">
                <img src="image/kinshen.jpg" alt="">
                <p class="caption">Kinshen N. Bahian</p>
                <p class="caption1">Artist</p>
            </div>
            <div class="slide">
                <img src="image/cat.jpg" alt="">
                <p class="caption">CaterenHope Dizon</p>
                <p class="caption1">Artist</p>
            </div>
            <div class="slide">
                <img src="image/frank.jpg" alt="">
                <p class="caption">Frank Anthony G. Pamisa</p>
                <p class="caption1">Artist</p>
            </div>
            <div class="slide">
                <img src="image/jay.jpg" alt="">
                <p class="caption">Jay Q. Sabuero</p>
                <p class="caption1">Artist</p>
            </div>
            <div class="slide">
                <img src="image/sam.png" alt="">
                <p class="caption">Sam C. Saligumba</p>
                <p class="caption1">Artist</p>
            </div>
            <div class="slide">
                <img src="image/shandy.jpg" alt="">
                <p class="caption">Shandy J. Salinas</p>
                <p class="caption1">Artist</p>
            </div>
            <div class="slide">
                <img src="image/eryle.jpg" alt="">
                <p class="caption">Eryle Kris S. Santarita</p>
                <p class="caption1">Artist</p>
            </div>
        </div>
    </div>
    <div class="now-playing-bar">
        <div class="song-info">
            <img src="image/music.jpg" alt="Album Cover" class="album-cover">
            <div class="song-details">
                <span class="song-title">Song Name</span>
                <span class="artist-name">Artist Name</span>
            </div>
        </div>
        <div class="controlsh">
            <button>⏮</button>
            <button>▶</button>
            <button>⏭</button>
        </div>
        <div class="progress-bar">
            <span>0:00</span>
            <input type="range" min="0" max="100" value="0">
            <span>3:45</span>
        </div>
    </div>
</body>
</html>



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Musify</title>
    <link rel="stylesheet" href="MusicPlaylist.css">
</head>
<body>
    <video autoplay loop muted plays-inline class="backgroundv">
        <source src="image/video.mp4" type="video/mp4">
    </video>
    <div class="header">
        <span>Musify</span>
        <input type="text" placeholder="Search">
        <div class="right-section">
            <span><img class="notif" src="image/notification.png"> Notifications</span>
            <span><img class="About" src="image/about us.png"> About Us</span>
            <a href="MusicLogin.html" style="color: white; text-decoration: none;"><span><img class="Account" src="image/account.png"> Account</span></a>
        </div>
    </div>
    <div class="sidebar">
        <div class="itemss">
            <a href="MusicHomePage.html" style="color: white; text-decoration: none;"><img class="icon" src="image/home.png"></a>
            <a href="MusicHomePage.html" style="color: white; text-decoration: none;"><div class="texts">Home</div></a>
        </div>
        <div class="itemss">
            <img class="icon" class="active1" src="image/playlists.png">
            <div class="texts" class="active1">Playlists</div>
        </div>
        <div class="itemss">
            <a href="MusicFavorites.html" style="color: white; text-decoration: none;"><img class="icon" src="image/favorites.png"></a>
            <a href="MusicFavorites.html" style="color: white; text-decoration: none;"><div class="texts">Favorites</div></a>
        </div>
        <div class="itemss">
            <a href="MusicNowPlaying.html" style="color: white; text-decoration: none;"><img class="icon" src="image/now playing.png"></a>
            <a href="MusicNowPlaying.html" style="color: white; text-decoration: none;"><div class="texts">Now Playing</div></a>
        </div>
        <div class="itemss">
            <a href="MusicRecentlyPlayed.html" style="color: white; text-decoration: none;"><img class="icon" src="image/recently played.png"></a>
            <a href="MusicRecentlyPlayed.html" style="color: white; text-decoration: none;"><div class="texts">Recently Played</div></a>
        </div>
        <div class="itemss">
            <img class="icon" src="image/settings.png">
            <div class="texts">Settings</div>
        </div>
        <div class="itemss">
            <img class="icon" src="image/logout.png">
            <div class="texts">Logout</div>
        </div>
    </div>
    <div class="playlist1">
        <div class="playlist-bar">
            <img src="image/music.jpg">
            <h2>Kinshen's Playlist</h2>
            <p>Kinshen N. Bahian</p>
        </div>
        <div class="playlist-bar">
            <img src="image/music.jpg">
            <h2>Cat's Playlist</h2>
            <p>CaterenHope Dizon</p>
        </div>
        <div class="playlist-bar">
            <img src="image/music.jpg">
            <h2>Frank's Playlist</h2>
            <p>Frank Anthony G. Pamisa</p>
        </div>
        <div class="playlist-bar">
            <img src="image/music.jpg">
            <h2>Jay's Playlist</h2>
            <p>Jay Q. Sabuero</p>
        </div>
        <div class="playlist-bar">
            <img src="image/music.jpg">
            <h2>Sam's Playlist</h2>
            <p>Sam C. Saligumba</p>
        </div>
        <div class="playlist-bar">
            <img src="image/music.jpg">
            <h2>Shandy's Playlist</h2>
            <p>Shandy J, Salinas</p>
        </div>
        <div class="playlist-bar">
            <img src="image/music.jpg">
            <h2>Eryle's Playlist</h2>
            <p>Eryle Kris S. Santarita</p>
        </div>
        <div class="playlist-bar">
            <img src="image/music.jpg">
            <h2>Sample Playlist</h2>
            <p>ARTIST</p>
        </div>
        <div class="playlist-bar">
            <img src="image/music.jpg">
            <h2>Sample Playlist</h2>
            <p>ARTIST</p>
        </div>
        <div class="playlist-bar">
            <img src="image/music.jpg">
            <h2>Sample Playlist</h2>
            <p>ARTIST</p>
        </div>
    </div>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Musify</title>
    <link rel="stylesheet" href="MusicPlaylist.css">
</head>
<body>
    <video autoplay loop muted plays-inline class="backgroundv">
        <source src="image/video.mp4" type="video/mp4">
    </video>
    <div class="header">
        <span>Musify</span>
        <input type="text" placeholder="Search">
        <div class="right-section">
            <span><img class="notif" src="image/notification.png"> Notifications</span>
            <span><img class="About" src="image/about us.png"> About Us</span>
            <a href="MusicLogin.html" style="color: white; text-decoration: none;"><span><img class="Account" src="image/account.png"> Account</span></a>
        </div>
    </div>
    <div class="sidebar">
        <div class="itemss">
            <a href="MusicHomePage.html" style="color: white; text-decoration: none;"><img class="icon" src="image/home.png"></a>
            <a href="MusicHomePage.html" style="color: white; text-decoration: none;"><div class="texts">Home</div></a>
        </div>
        <div class="itemss">
            <a href="MusicPlaylists.html" style="color: white; text-decoration: none;"><img class="icon" src="image/playlists.png"></a>
            <a href="MusicPlaylists.html" style="color: white; text-decoration: none;"><div class="texts">Playlists</div></a>
        </div>
        <div class="itemss">
            <img class="icon" class="active2" src="image/favorites.png">
            <div class="texts" class="active2">Favorites</div>
        </div>
        <div class="itemss">
            <a href="MusicNowPlaying.html" style="color: white; text-decoration: none;"><img class="icon" src="image/now playing.png"></a>
            <a href="MusicNowPlaying.html" style="color: white; text-decoration: none;"><div class="texts">Now Playing</div></a>
        </div>
        <div class="itemss">
            <a href="MusicRecentlyPlayed.html" style="color: white; text-decoration: none;"><img class="icon" src="image/recently played.png"></a>
            <a href="MusicRecentlyPlayed.html" style="color: white; text-decoration: none;"><div class="texts">Recently Played</div></a>
        </div>
        <div class="itemss">
            <img class="icon" src="image/settings.png">
            <div class="texts">Settings</div>
        </div>
        <div class="itemss">
            <img class="icon" src="image/logout.png">
            <div class="texts">Logout</div>
        </div>
    </div>
    <div class="favorites">
        <div class="fav-bar">
            <img src="image/music.jpg">
            <h2>Kinshen's Playlist🖤</h2>
            <p>Kinshen N. Bahian</p>
        </div>
        <div class="fav-bar">
            <img src="image/music.jpg">
            <h2>Cat's Playlist 🖤</h2>
            <p>CaterenHope Dizon</p>
        </div>
        <div class="fav-bar">
            <img src="image/music.jpg">
            <h2>Frank's Playlist 🖤</h2>
            <p>Frank Anthony G. Pamisa</p>
        </div>
        <div class="fav-bar">
            <img src="image/music.jpg">
            <h2>Jay's Playlist 🖤</h2>
            <p>Jay Q. Sabuero</p>
        </div>
        <div class="fav-bar">
            <img src="image/music.jpg">
            <h2>Sam's Playlist 🖤</h2>
            <p>Sam C. Saligumba</p>
        </div>
        <div class="fav-bar">
            <img src="image/music.jpg">
            <h2>Shandy's Playlist 🖤</h2>
            <p>Shandy J, Salinas</p>
        </div>
        <div class="fav-bar">
            <img src="image/music.jpg">
            <h2>Eryle's Playlist 🖤</h2>
            <p>Eryle Kris S. Santarita</p>
        </div>
        <div class="fav-bar">
            <img src="image/music.jpg">
            <h2>Sample Playlist 🖤</h2>
            <p>ARTIST</p>
        </div>
        <div class="fav-bar">
            <img src="image/music.jpg">
            <h2>Sample Playlist 🖤</h2>
            <p>ARTIST</p>
        </div>
        <div class="fav-bar">
            <img src="image/music.jpg">
            <h2>Sample Playlist 🖤</h2>
            <p>ARTIST</p>
        </div>
    </div>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Musify</title>
    <link rel="stylesheet" href="MusicPlaylist.css">
</head>
<body>
    <video autoplay loop muted plays-inline class="backgroundv">
        <source src="image/video.mp4" type="video/mp4">
    </video>
    <div class="header">
        <span>Musify</span>
        <input type="text" placeholder="Search">
        <div class="right-section">
            <span><img class="notif" src="image/notification.png">Notifications</span>
            <span><img class="About" src="image/about us.png">About Us</span>
            <a href="MusicLogin.html" style="color: white; text-decoration: none;"><span><img class="Account" src="image/account.png"> Account</span></a>
        </div>
    </div>
    <div class="sidebar">
        <div class="itemss">
            <a href="MusicHomePage.html" style="color: white; text-decoration: none;"><img class="icon" src="image/home.png"></a>
            <a href="MusicHomePage.html" style="color: white; text-decoration: none;"><div class="texts">Home</div></a>
        </div>
        <div class="itemss">
            <a href="MusicPlaylists.html" style="color: white; text-decoration: none;"><img class="icon" src="image/playlists.png"></a>
            <a href="MusicPlaylists.html" style="color: white; text-decoration: none;"><div class="texts">Playlists</div></a>
        </div>
        <div class="itemss">
            <a href="MusicFavorites.html" style="color: white; text-decoration: none;"><img class="icon" src="image/favorites.png"></a>
            <a href="MusicFavorites.html" style="color: white; text-decoration: none;"><div class="texts">Favorites</div></a>
        </div>
        <div class="itemss">
            <img class="icon" class="active" src="image/now playing.png">
            <div class="texts" class="active">Now Playing</div>
        </div>
        <div class="itemss">
            <a href="MusicRecentlyPlayed.html" style="color: white; text-decoration: none;"><img class="icon" src="image/recently played.png"></a>
            <a href="MusicRecentlyPlayed.html" style="color: white; text-decoration: none;"><div class="texts">Recently Played</div></a>
        </div>
        <div class="itemss">
            <img class="icon" src="image/settings.png">
            <div class="texts">Settings</div>
        </div>
        <div class="itemss">
            <img class="icon" src="image/logout.png">
            <div class="texts">Logout</div>
        </div>
    </div>
    <div class="main-content">
        <h1 style="color: white; text-decoration: none;">best of 2020’s</h1>
        <div class="now-playing">
            <img src="image/music.jpg" alt="Album Cover">
            <marquee behavior="scroll" direction="left" scrollamount="7"> <h3>SAMPLE TITLE</h3></marquee>
            <p>ARTIST</p>
            <input type="range" id="progress" value="0" max="100" step="0.1">
            <span id="current-time">0:00</span> / <span id="duration">0:00</span>
            <div class="controls">
                <button>&#8634;</button>
                <button>⏮</button>
                <button>▶</button>
                <button>⏭</button>
            </div>
        </div>
    </div>
    <div class="playlist">
                <div class="song">
                    <img src="image/music.jpg" alt="Album">
                    <div class="info">
                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>BAHIAN song's</h4></marquee>
                        <p>BAHIAN</p>
                    </div>
                    <button>&#9654;</button>
                </div>
                <div class="song">
                    <img src="image/music.jpg" alt="Album">
                    <div class="info">
                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>DIZON song's</h4></marquee>
                        <p>DIZON</p>
                    </div>
                    <button>&#9654;</button>
                </div>
                <div class="song">
                    <img src="image/music.jpg" alt="Album">
                    <div class="info">
                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>PAMISA song's</h4></marquee>
                        <p>PAMISA</p>
                    </div>
                    <button>&#9654;</button>
                </div>
                <div class="song">
                    <img src="image/music.jpg" alt="Album">
                    <div class="info">
                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SABUERO song's</h4></marquee>
                        <p>SABUERO</p>
                    </div>
                    <button>&#9654;</button>
                </div>
                <div class="song">
                    <img src="image/music.jpg" alt="Album">
                    <div class="info">
                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SALIGUMBA song's</h4></marquee>
                        <p>SALIGUMBA</p>
                    </div>
                    <button>&#9654;</button>
                </div>
                <div class="song">
                    <img src="image/music.jpg" alt="Album">
                    <div class="info">
                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SALINAS song's</h4></marquee>
                        <p>SALINAS</p>
                    </div>
                    <button>&#9654;</button>
                </div>
                <div class="song">
                    <img src="image/music.jpg" alt="Album">
                    <div class="info">
                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SANTARITA song's</h4></marquee>
                        <p>SANTARITA</p>
                    </div>
                    <button>&#9654;</button>
                </div>
                <div class="song">
                    <img src="image/music.jpg" alt="Album">
                    <div class="info">
                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>
                        <p>ARTIST</p>
                    </div>
                    <button>&#9654;</button>
                </div>
                <div class="song">
                    <img src="image/music.jpg" alt="Album">
                    <div class="info">
                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>
                        <p>ARTIST</p>
                    </div>
                    <button>&#9654;</button>
                </div>
                <div class="song">
                    <img src="image/music.jpg" alt="Album">
                    <div class="info">
                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>
                        <p>ARTIST</p>
                    </div>
                    <button>&#9654;</button>
                </div>
                <div class="song">
                    <img src="image/music.jpg" alt="Album">
                    <div class="info">
                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>
                        <p>ARTIST</p>
                    </div>
                    <button>&#9654;</button>
                </div>
                <div class="song">
                    <img src="image/music.jpg" alt="Album">
                    <div class="info">
                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>
                        <p>ARTIST</p>
                    </div>
                    <button>&#9654;</button>
                </div>
                <div class="song">
                    <img src="image/music.jpg" alt="Album">
                    <div class="info">
                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>
                        <p>ARTIST</p>
                    </div>
                    <button>&#9654;</button>
                </div>
            </div>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Musify</title>
    <link rel="stylesheet" href="MusicPlaylist.css">
</head>
<body>
    <video autoplay loop muted plays-inline class="backgroundv">
        <source src="image/video.mp4" type="video/mp4">
    </video>
    <div class="header">
        <span>Musify</span>
        <input type="text" placeholder="Search">
        <div class="right-section">
            <span><img class="notif" src="image/notification.png"> Notifications</span>
            <span><img class="About" src="image/about us.png"> About Us</span>
            <a href="MusicLogin.html" style="color: white; text-decoration: none;"><span><img class="Account" src="image/account.png"> Account</span></a>
        </div>
    </div>
    <div class="sidebar">
        <div class="itemss">
            <a href="MusicHomePage.html" style="color: white; text-decoration: none;"><img class="icon" src="image/home.png"></a>
            <a href="MusicHomePage.html" style="color: white; text-decoration: none;"><div class="texts">Home</div></a>
        </div>
        <div class="itemss">
            <a href="MusicPlaylists.html" style="color: white; text-decoration: none;"><img class="icon" src="image/playlists.png"></a>
            <a href="MusicPlaylists.html" style="color: white; text-decoration: none;"><div class="texts">Playlists</div></a>
        </div>
        <div class="itemss">
            <a href="MusicFavorites.html" style="color: white; text-decoration: none;"><img class="icon" src="image/favorites.png"></a>
            <a href="MusicFavorites.html" style="color: white; text-decoration: none;"><div class="texts">Favorites</div></a>
        </div>
        <div class="itemss">
            <a href="MusicNowPlaying.html" style="color: white; text-decoration: none;"><img class="icon" src="image/now playing.png"></a>
            <a href="MusicNowPlaying.html" style="color: white; text-decoration: none;"><div class="texts">Now Playing</div></a>
        </div>
        <div class="itemss">
            <img class="icon" class="active" src="image/recently played.png">
            <div class="texts" class="active">Recently Played</div>
        </div>
        <div class="itemss">
            <img class="icon" src="image/settings.png">
            <div class="texts">Settings</div>
        </div>
        <div class="itemss">
            <img class="icon" src="image/logout.png">
            <div class="texts">Logout</div>
        </div>
    </div>
    <div class="playlist4">
        <div class="song">
            <img src="image/music.jpg" alt="Album">
            <div class="info">
                <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>BAHIAN song's</h4></marquee>
                <p>BAHIAN</p>
            </div>
            <button>&#9654;</button>
        </div>
        <div class="song">
            <img src="image/music.jpg" alt="Album">
            <div class="info">
                <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>DIZON song's</h4></marquee>
                <p>DIZON</p>
            </div>
            <button>&#9654;</button>
        </div>
        <div class="song">
            <img src="image/music.jpg" alt="Album">
            <div class="info">
                <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>PAMISA song's</h4></marquee>
                <p>PAMISA</p>
            </div>
            <button>&#9654;</button>
        </div>
        <div class="song">
            <img src="image/music.jpg" alt="Album">
            <div class="info">
                <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SABUERO song's</h4></marquee>
                <p>SABUERO</p>
            </div>
            <button>&#9654;</button>
        </div>
        <div class="song">
            <img src="image/music.jpg" alt="Album">
            <div class="info">
                <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SALIGUMBA song's</h4></marquee>
                <p>SALIGUMBA</p>
            </div>
            <button>&#9654;</button>
        </div>
        <div class="song">
            <img src="image/music.jpg" alt="Album">
            <div class="info">
                <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SALINAS song's</h4></marquee>
                <p>SALINAS</p>
            </div>
            <button>&#9654;</button>
        </div>
        <div class="song">
            <img src="image/music.jpg" alt="Album">
            <div class="info">
                <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SANTARITA song's</h4></marquee>
                <p>SANTARITA</p>
            </div>
            <button>&#9654;</button>
        </div>
        <div class="song">
            <img src="image/music.jpg" alt="Album">
            <div class="info">
                <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>
                <p>ARTIST</p>
            </div>
            <button>&#9654;</button>
        </div>
        <div class="song">
            <img src="image/music.jpg" alt="Album">
            <div class="info">
                <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>
                <p>ARTIST</p>
            </div>
            <button>&#9654;</button>
        </div>
        <div class="song">
            <img src="image/music.jpg" alt="Album">
            <div class="info">
                <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>
                <p>ARTIST</p>
            </div>
            <button>&#9654;</button>
        </div>
        <div class="song">
            <img src="image/music.jpg" alt="Album">
            <div class="info">
                <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>
                <p>ARTIST</p>
            </div>
            <button>&#9654;</button>
        </div>
        <div class="song">
            <img src="image/music.jpg" alt="Album">
            <div class="info">
                <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>
                <p>ARTIST</p>
            </div>
            <button>&#9654;</button>
        </div>
        <div class="song">
            <img src="image/music.jpg" alt="Album">
            <div class="info">
                <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>
                <p>ARTIST</p>
            </div>
            <button>&#9654;</button>
        </div>
    </div>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}
.backgroundv{
    position: fixed;
    right: 0;
    bottom: 0;
    width: 100vw;
    height: 100vh;
    object-fit: cover;
    z-index: -1;
}
body {
    background: #ddd;
    display: flex;
    flex-direction: column;
    height: 100vh;
    overflow: hidden;
}
.header {
    width: 100%;
    background: #294E28;
    color: white;
    padding: 10px 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: fixed;
    top: 0;
    left: 0;
    height: 50px;
    font-size: 20px;
    z-index: 1000;
}
.header input {
    width: 400px;
    padding: 5px;
    border-radius: 5px;
    border: none;
    margin-left: 20px;
}
.header .right-section {
    display: flex;
    align-items: center;
    gap: 50px;
    cursor: pointer;
}

.notif {
    position: absolute;
    height: 35px;
    width: 35px;
    top: 7px;
    right: 385px;
}

.About {
    position: absolute;
    height: 25px;
    width: 25px;
    top: 11px;
    right: 225px;
}

.Account {
    position: absolute;
    height: 25px;
    width: 25px;
    top: 11px;
    right: 95px;
}
.sidebar {
    width: 60px;
    height: 100vh;
    position: fixed;
    top: 30px;
    left: 0;
    padding: 10px;
    background-color: #084017;
    color: white;
    overflow: hidden;
    transition: width 0.3s ease-in-out;
    z-index: 1;
}
.sidebar:hover {
    width: 200px;
}
.sidebar:hover .itemss .text {
    opacity: 1;
    visibility: visible;
    cursor: pointer;
}
.itemss {
    display: flex;
    align-items: center;
    margin: 20px 0;
    cursor: pointer;
}
.itemss .icon {
    width: 40px;
    height: 35px;
    flex-shrink: 0;
    fill: white;
    margin-right: 15px;
    cursor: pointer;
}
.itemss .text {
    opacity: 0;
    visibility: hidden;
    transition: opacity 0.3s ease-in-out, visibility 0.3s ease-in-out;
    margin-left: 15px;
    white-space: nowrap;
    cursor: pointer;
}
.sidebar .active, 
.sidebar .active1,
.sidebar .active2,
.sidebar .active3,
.sidebar .active4 {
    background: white;
    color: black;
    border-radius: 10px;
    padding: 5px;
}

.main-home {
    display: flex;
    position: absolute;
    width: 700px;
    height: 300px;
    top: 50px;
    left: 30px;
    padding: 10px;
}
.main-home .musify {
    position: absolute;
    width: 680px;
    height: 260px;
    padding: 10px;
}
.main-home .musify-logo {
    position: absolute;
    width: 260px;
    height: 260px;
    left: 600px;
    padding: 10px;
}
.home-search {
    position: absolute;
    width: 500px;
    height: 40px;
    left: 60px;
    bottom: 0;
    margin-top: 100px;
    border-radius: 10px;
}

.category-side {
    width: 620px;
    position: absolute;
    top: 55px;
    right: 0px;
    display: inline-block;
    gap: 20px;
    height: 340px;
}
.category {
    font-size: 1.5rem;
    font-weight: bold;
    color: white;
    margin-bottom: 15px;
    width: 600px;
}
.category-box {
    position: relative;
    width: 140px;
    height: 140px;
    padding: 10px;
    display: inline-block;
    margin-bottom: 10px;
    margin-right: 10px;
    cursor: pointer;
}
.category-box:hover {
    transform: scale(0.9);
}
.category-box img {
    position: absolute;
    inset: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 10px;
}
.category-box p {
    font-size: 1rem;
    position: absolute;
    bottom: 5px;
    font-weight: bold;
    color: white;
}

.carousel {
    overflow: hidden;
    width: 96%;
    position: absolute;
    bottom: 80px;
    left: 62px;
}
.Popular-Artist {
    font-size: 1.5rem;
    font-weight: bold;
    color: white;
    margin-bottom: 5px;
}
.caption {
    margin-top: 5px;
    font-size: 1.3rem;
    color: white;
    font: bolder;
}
.caption1 {
    margin-top: 1px;
    font-size: 0.9rem;
    color: white;
    font-style: italic;
}
.wrap {
    display: grid;
    grid-auto-flow: column;
    grid-auto-columns: 250px;
    justify-items: stretch;
    animation: slide 15s linear infinite;
    width: max-content;
}
.wrap img {
    width: 200px;
    height: 200px;
    border-radius: 100px;
    object-fit: cover;
}
@keyframes slide {
    to {
        translate: calc(-4 * 250px);
    }  
}

.now-playing-bar {
    position: fixed;
    bottom: 0;
    width: 100%;
    background: transparent;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    backdrop-filter: blur(30px);
    box-shadow: 0px 0px 30px rgba(227, 228, 237, 0.37);
    border: 1.5px solid rgba(255, 255, 255, 0.18);
    z-index: 1;
}
.song-info {
    display: flex;
    align-items: center;
}
.album-cover {
    width: 50px;
    height: 50px;
    border-radius: 5px;
    margin-right: 10px;
}
.song-details {
    display: flex;
    flex-direction: column;
}
.song-title {
    font-weight: bold;
}
.controlsh {
    position: inherit;
    align-items: center;
    right: 31%;
    margin-bottom: 6px;
}
.controlsh button {
    background: none;
    border: none;
    color: white;
    font-size: 20px;
    cursor: pointer;
    margin: 0 5px;
}
.progress-bar {
    display: flex;
    align-items: center;
    width: 30%;
}
.progress-bar input {
    width: 100%;
    margin: 0 10px;
}

.playlist1 {
    width:1340px;
    position: absolute;
    top: 70px;
    right: 0; 
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    align-items: center;
}
.playlist-bar {
    display: inline-block;
    height: 300px;
    width: 30vh;
    background-color: #126527;
    margin: 15px;
    margin-top: 0;
    padding: 10px;
    border-radius: 15px;
}
.playlist-bar img {
    height: 220px;
    width: 200px;
    border-radius: 15px;
}
.playlist-bar h2 {
    font-size: 23px;
}
.playlist-bar p {
    font-size: 13px;
}

.favorites {
    width:1340px;
    position: absolute;
    top: 70px;
    right: 0; 
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    align-items: center;
}
.fav-bar {
    display: inline-block;
    height: 300px;
    width: 30vh;
    background-color: #126527;
    margin: 15px;
    margin-top: 0;
    padding: 10px;
    border-radius: 15px;
}
.fav-bar img {
    height: 220px;
    width: 100%;
    border-radius: 15px;
}
.fav-bar h2 {
    font-size: 20px;
}
.fav-bar p {
    font-size: 13px;
}

.main-content {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 20px;
    margin-left: 200px;
    margin-top: 50px;
    width: calc(100% - 900px);
}

.now-playing {
    text-align: center;
    background: rgb(45, 94, 10);
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
    width: 500px;
    height: 530px;
}
.now-playing img {
    width: 100%;
    height: 380px;
    border-radius: 10px;
}
.controls {
    display: flex;
    justify-content: center;
    margin-top: 10px;
}
.controls button {
    background: none;
    border: none;
    font-size: 24px;
    cursor: pointer;
    margin: 0 10px;
}

.playlist {
    width: 700px;
    padding: 10px;
    position: fixed;
    right: 0;
    top: 50px;
    height: calc(100vh - 50px);
    overflow-y: auto;
}
.song {
    background: #126527;
    color: white;
    padding: 10px;
    margin: 8px 0;
    border-radius: 15px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    max-width: 1000px;
    height: 70px;
    font-size: 16px;
}
.song .info {
    flex: 1;
}
.song img {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    margin-right: 10px;
}   
.song button {
    background: none;
    border: none;
    color: white;
    font-size: 25px;
    cursor: pointer;
}

.playlist4 {
    width: 1000px;
    padding: 10px;
    position: fixed;
    right: 0;
    top: 50px;
    height: calc(100vh - 50px);
    overflow-y: auto;
}
