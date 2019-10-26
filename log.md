<h1 align="center">100 Days Of Code with Anthony Gerrard</h1>

<img src="https://images.unsplash.com/photo-1454165205744-3b78555e5572?dpr=1&auto=format&fit=crop&w=1500&h=1000&q=80&cs=tinysrgb&crop=&bg=" alt="Image of laptop with code">

Hello World! You are about to witness the beginning of an epic 100-day coding journey: A story that great sages will pass down from generation to generation. This quest will feature a potpourri of unfiltered joy, unrivaled pain, and unexpected epiphanies.

Some moments, I will feel like the smartest man alive. Others moments, I will feel like a stupid idiot. But each day, I will be a valiant warrior, fighting to improve my development skills on my mission to getScript('Or Die Tryin').
 
Without further ado, I present **#100DaysofCode with _Anthony Gerrard_**.

<img src="https://lh3.googleusercontent.com/3viPbSWDRmvVorilc0TghACggKHIwOfFhSDNBWDbiFEEyKVFqqqwogT7XhEy_OaBoachdL4r2UtXxSy6WOBBSzzk0DVI7S7LV1THoFs8CkKhWU_ElzewItZ12yPym4OHl_AK91pQwA=w1000-h758-no" alt="Headshot of Joe Warren">

<p align="center"><b>Follow me on Twitter </b><a href="http://www.twitter.com/swtmouthedtony">here</a>.</p>

<p align="center"><b>Check out my repos </b><a href="https://github.com/mrpc4">here</a>.</p>
<hr>
<br>

<h2 align="center">
Day 1: Wednesday February 1, 2017
</h2>
 
**Today's Progress**: I've been working on a minutes to hours converter, and I was able to figure out the JavaScript code to make the conversion happen when clicking the Convert button.

**Thoughts** I've been coding regularly since December 2016, but this was my first independent project. When a user inputs a number, the output would be that number of minutes in hours. I created an if/else statement for if userInput is 60 (the "hours" string would be singular in that case). I didn't look at any code for the statement so needless to say, I felt like a BOSS.
```
<script>
    function outputHours() {
        var minutes=document.getElementById("userInput").value;
        var hours=minutes/60;
        if (minutes == 60) {
                alert(minutes + " minutes = " + hours + " hour"); //If input is 60 minutes, outputs 'hour' since 1 hour is singular
            } 
            else {
                alert(minutes + " minutes = " + hours + " hours"); //outputs 'hours' for anything that is not 60 minutes
            }
        }
    </script>
```
Also, I figured out how to show the answer in the console and as a pop up, but I couldn't figure out how to write it to the screen while controlling the placement.

**Link to tweet**
[MightyJoeW Day 1](https://twitter.com/MightyJoeW/status/826959358391107584)


<h2 align="center">
Day 2: Thursday February 2, 2017
</h2> 

**Today's Progress**: Got the web version of my minutes to hours converter looking decent. However, the mobile view was UGLY!

> Exhibit A - Early Web View
<img src="https://lh3.googleusercontent.com/rjzi8Y7JAI8F1WX4exGHdeS58za2AO0OtzP5rwZ62TGxtcOzqhk3IVfW3vDohmPEm-1ApKiVyFxHNwiJHxJk02rjgYPO-EPZirt_uJHEoJlc7Ehv_Mbxd487HTsasbGVkJQCp6ObXSk89cvHBGk-ls6Z_a51rPF0YBlCXyQY9Lh0BVnzuOLKWo9m3fMswg_z47etG37fH0xkcKqRz-Dk53QppMZpXaW4NHPGlRj8HVedVsgoLwXAJ5IDUqHI9NnjB1m2DfSQjIvhmKk_AdZKsgskoEwCCdJFAT0Rss0g3_L38znuEsbWpFkd9WSKdPVaTJFISLb-yoIYe8vM49Ilz630A2OHatFXiKwoWBkSjYjTLZ8AMk-UxqoXyp-5nPeG8mcbnfLqhqnxPwUjU5V8SSWzdU_N0rEh0-SG3o1ltKtjwRvPshbcPrOkDUPpDLf3apNGQjPNAwTtF6RpRxllVXDDyPE8Itw1Z3uOhR5WNckgrjTtWPktwFgJADlB1vVKFZlfXJapG1m0Tu5M700w1C3fDqOkTGwpuXoURj1V0R4lb7gOGPk_L5jnu0YVRddhx5iNq13QtTWeg7Pp8BO-iSQ5sVh8Kf63H9_P-ThBoNSgO8lTnef4lg=w1139-h627-no" alt="Early Web Minutes Converter">

> Exhibit B - Hideous Mobile View
<img src="https://lh3.googleusercontent.com/duicZ0g5NdFgAAxhao9qcClaGp5828f263Q1eX1ILdF5UtIvy8QmAOjP1FFu1ABydbCIBwzNR-CiOyKQg2yuLTEUCOpMmh3jcUj8Ny8KGTovw3WcFgKp-ILViGQKTUWsjD4hBdwzkQPbIyd9ilCtQlyVIiBToBVue9ja_cFh4_gfk-bUsKRCnqtX1qcnXZD7ZdeSYVQRyFcj3reLzOmvtcLQiyfsCdUmxnLFcNep4VUhg5cg8UQiyzLSSVjyVMZXe68TB_Sggh2m609Bi5HBuWXuyX2SIwsH5uyvTys2CYppMyRTwOUTakvtnfzBkpPZECRrGR0JF0ZsuXHWmOeavIi2_a5tNKQF3oxPLsyuqfX-kjI0p263LzcHgAmd1BVChfpzhh10lKVtBTBCGG4aakSblmH9SS4R1xWWgs_mlFCFZoFxMkFSQHpDJAJPn9t2V6TvAth4nR_sKh41Rb6prEb3VI45AUwJfvLIM2qzqyIW7E8pcNhnffTrzp75pIoRylMInRAMRWmCS-2XWUvNEftSyFgoh7ORiiyzQ28_hr7d2YiCIMOhTQPTtJnzKkR_PFYAQPSCPCFqFDhMpjbRVOMWD5E6iYe7FB5hijyDWtirXQveSzowfA=w365-h627-no" alt="Ugly Minutes Converter">

Specific steps:
- Added footer with copyright 
- Changed background (removed clock img since it looked bad on narrow pages, made a gradient background in CSS). On second thought, just made background white. Not sure if backgrounds looks tacky here.
- Bolded Minutes label

**Thoughts:** Today was a really fun day. I initially had a background on the minutes conveter, but I noticed that it clashed with the form on narrow pages. I removed the background which made the page look plain, but it was good enough for the time being. Then, I pasted my code to Codepen to check how it looks on phones. You can see the results in my tweet lol. The fixed Footer was in the middle of the page, and everything else looked sloppy. That gave me a good laugh as I looked forward to figuring this thing out.

**Link to tweet:** [MightyJoeW Day 2](https://twitter.com/MightyJoeW/status/827239030563696640)


<h2 align="center">
Day 3: Friday February 3, 2017
</h2>   

**Today's Progress**: Finished the Minutes to Hour Converter! Well, at least for now...

<div>
  <img src="https://lh3.googleusercontent.com/x3cZN1jiu0z1SAQ8zPyPaoYK3MXZYmVh8bCBz_T2LewZEfJrzBRTjUZCj4s8pMMlYIHBDzoZDLrEpcH9vPe0Sq4v8mujqKP3AzxHkzACMr-DuBiTIwKzcOFL51rC9YKirqlgPwLNZEAC6H8n85Cz9HHXl4xK0y2knOEvhwQJ1IHFoz_6U_6I7VJM97CL-KP8DI1_eRXw3spsXvuWhHt78GFA9SLQ22Alx07LAAUc5nQ9tGuV8PAj-TmZKdVwI8Vhugm1dicf5vugX44EXEz3j0e83zHh0LR_IgFJk428S2YDzxUiQk-SXEd-LFFvlj9u_xsnvgl8YS9D6QNbGTgJSM8o64NB_whsZOnIyx_7JzxZ27ZUeLX1ehwkH-slydknEykdXkRxFomif-773IaDLFIZYXV3PtwJQv5K3EUtVAmW1U37gpPkWLssEXcgCFu3rHQoXhuaZpDdbqsxjIxQ5eorCwLnoiLsk5Ea8K0L6W-N5wMlzimRaerR8EZgb1ERbUtBinGfnu0lVS3RCe7fApjH28ClAUXVXQJ4VoMfgYcC5Mlr7ggl3JHUX8xylhViKmwDcGyB2U_W8ixQ62X-GxLzX3sGkOWw3n6IPrDNnAseQ1Q11aKyvg=w411-h703-no" style="float: left;" alt="Mobile Minutes Converter">
  
  <img src="https://lh3.googleusercontent.com/Hr7vHmCip7-GJw7q0VNu_5I-0KVVJjIXLgtdXi7aoDUnLrfhfMByyHstQV9HU6m5oLfSxt1IghXeZ7ur7zr3_Jufc59vQysALzpFR4-Q1tjIGjgVuKg8fCki-PiH1rJxjrIBsdCGhuCEoVaVAABZpxrxSQ02DC1LjivldliEKjFYjBLycpUb-2vJiR5ktZ-8uxo52HAUCbAZJhP9bx1gJqF-tAuDRdR_oY6jEB_GQ8fUBK59Fb_4itWzysNbBFsFG1XwjW_hlsB3e-ASqD8q2lqRYRF0nGYCxuqaiBJWMu1Rr4YRqERtmIKYOBjDI5zwB4TsX-f9q0G03ndb9I5W_FmRBy4R5pnEfVJJHKOGyyiRL4Xc3NV9Gg32SkzpdF4IpJAvdmhzwgJNqkx85Vr0X5pDFgpUaJo108MQzBdiIEGml4lnl-GJ3113Z313T5jSz-FWrrjcsQ1PjbJ8n2VDzDwUByqV5VqEOItA3fYMDE_de6o2yBvHSPlD1p8yaF1HEFZZh0fVEmyS9DA6JGU48rBmPy8uQbLH_j5xKi4V5bfo4YwI1vpbbroJWPtUUxCidRDQSIi9SdHz7HYAhUHz31DfZ4eHOOokZodbUDmELlCRcxOGhUmAxA=w412-h703-no" style="float: left;" alt="Mobile Minutes Converter">
</div>

- Added `lang="en-us"` to HTML
- Added `<meta name=""viewport"" content=""width=device-width, initial-scale=1.0"">` (trying to make mobile friendly)
- Removed parenthesis from around. It looked **BAD** on mobile.
- Added mobile friendly code from [W3 Schools](https://www.w3schools.com/) in `.body`. Can't figure out how to move everything to the center now... Found it!!! Change margin to `auto`!!
- Fixed Footer on mobile by changing position from `absolute` to `fixed` :smile:

**Thoughts:** It felt really good completing my first little project (especially without using jQuery or Bootstrap). I intentionally decided not to use those as I'm still early in learning JavaScript and want to have a better understanding of it first. Plus, it sounds like they are losing popularity anyway. 


**Link to tweet:** [MightyJoeW Day 3](https://twitter.com/MightyJoeW/status/827548443614859264)

**Link to work:** [Minutes to Hour Converter (Codepen link)](http://codepen.io/MightyJoeW/full/qRoeYy/)


<h2 align="center">
Day 4: Saturday February 4, 2017
</h2>
<img src="http://www.aha.io/assets/github.7433692cabbfa132f34adb034e7909fa.png" alt"Github logo">

**Today's Progress**: Learned my way around GitHub.

**Thoughts:** At this past Free Code Camp meetup, we spent a lot of time in GitHub. I felt like it was moving too fast, so I really wanted to get a grasp on how to use GitHub using [GitHub Guides](https://guides.github.com/). It looked like I was looking at gibberish before, but now it makes a lot more sense.  

**Link to tweet:** [MightyJoeW Day 4](https://twitter.com/MightyJoeW/status/827932053660397569)

**My GitHub:** [MightyJoeW](https://github.com/MightyJoeW)


<h2 align="center">
Day 5: Sunday February 5, 2017
</h2>  

<img src="https://react-etc.net/files/2016-07/logo-578x270.png" alt="ReactJs">

**Today's Progress**: Spent more time learning how to use GitHub. Then, worked with Node.js and React for the first time at Free Code Camp. 

**Thoughts:** It's amazing how quickly you can go from feeling on top of the world to feeling like you know absolutely nothing. This happens often to me at our Free Code Camp meetups lol. I have a decent understanding of HTML and CSS, and I'm getting more comfortable with JavaScript, but I have never seen Node.js or React before. 

<img src="http://i.imgur.com/c4jt321.png" alt="ReactJs">

I felt like my brain was put in a blender, but I was happy to get exposed to both of these early in my learning. I've wanted to learn both, and I got a little preview of what they both are like. 

**Link to tweet:** [MightyJoeW Day 5](https://twitter.com/MightyJoeW/status/828369204793446400)

**Link to work:** [Free Code Camp](http://freecodecampdallas.com/)


<h2 align="center">
Day 6: Monday February 6, 2017
</h2>  

**Today's Progress**: Morning - Free Code Camp lessons. Evening - Got my first HTTP server up and running with node.js.

**Thoughts:** Node.js seems to be functioning properly. However, Express is still giving me issues. I don't think everything installed correctly (I saw some errors). Also, when trying to open package.json, I get the following: 

```
 {
 "name": "myapp",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC"
}
```

Being new to all of this, it's too early for me to even know what to look for in regards to what's going wrong. I'm going to keep pushing the next few days because I want to get this all set up and be able to shift more of my attention back to coding. Not a fun day of coding, but an important one.

**Link to tweet:** [MightyJoeW Day 6](https://twitter.com/MightyJoeW/status/828813131988217857)

**Link to work:** [Nodejs Tutorial](https://www.tutorialspoint.com/nodejs/nodejs_npm.htm)


<h2 align="center">
Day 7: Tuesday February 7, 2017
</h2> 

**Today's Progress**: Reviewed HTML and CSS. Created a few basic HTML pages including a Pokemon chart and a login page.

**Thoughts:** I decided to try out Udemy's [Web Developer Bootcamp by Colt Steele](https://www.udemy.com/the-web-developer-bootcamp/). It's currently $15 (regular price $200), and I had seen many different people comment about how great this content is. I've been getting stuck on FCC challenges and felt like a needed a solid training program to go along with it. So far, it's been great!

A couple of simple things I've picked up already are many helpful shortcuts in Sublime Text as well as how to hyperlink to a local file (relative path). I only knew how to hyperlink other web pages. The rest has been a good review of some HTML and CSS things I've forgotten.

**Sidenote Jones:** I never imagined growing up that I'd be seeing Pokemon in learning material (or dominating mainstream news and media like when Pokemon Go took off). I still have my original Pokemon Yellow and Silver (I gave my Red and Blue away along with my wrestling action figures in a garage sale when we moved back in the day).

**Link to tweet:** [MightyJoeW Day 7](https://twitter.com/MightyJoeW/status/829134236686942208)

**Link to work:** [First Gen Pokemon Chart](https://codepen.io/MightyJoeW/full/zNJNQQ/)


<h2 align="center">
Day 8: Wednesday February 8, 2017 
</h2>

**Today's Progress**: Week 1 complete! More HTML and CSS review (working through Udemy's Web Developer Bootcamp by Colt Steele). Practiced CSS with an 'About Me' page and a 'To Do list' page.

<img src="https://lh3.googleusercontent.com/SsQaWdf1OoPEuVct6-OivZTleXCJsolfv5YErb_smxNZ3-ncvKSAazCPBeus1pBb1sFw9fXdrmNQ9_DJwsmVsVunZw1UdzW-paOa0dto8yoPXE_3oIL8KFfOX2t-DnphVbBodtqedUiQHq1PhCaVorR7jwtnJ5T3EQ637JugsRgbzCsoS-uhzjl7KfrPRqT5KooT-CgkwpCjklwF0o3KzHSdFXD-yqKEI2jEl6KKpQJhmhh92kHkyq8_9zop90vtOuQw4npHjY20T9gzqKzS9W8g45UoBpd5KCG0M8gqj8_LORflZtk5JaAAH_hqjGZNiGBmPeKoGWhkvjHSN8kVTYXIdl8eIa1KICtwFnwg-fpz1mvxB7or_98x8LqdxcGdPjtqq497FPki2uN9JV1ootj6KyyxEHXSECF6rpabcNgsiusJQtgaS4BILNPj752sc9p3XC1RHM7nn_cNKBlZbmKMqGbkvhgGrkwqEMc3GwdWLTr-NifrH5KMaR4dRRGlXLdUP0jnVvXVnwVVVMrXuqLH7ShBx_KfWj2vKvcID45vqYMGmOV0v98Ms3qZImKRZuC9X659Gij5gdnTlk0RSpFRCJwWMlNTGSjO2w5rZBoc0GzFUGPIuQ=w1274-h199-no" alt="Basic To Do List">

```
<body>
<h1>To Do List</h1>

<ul>
	<li id="priority" class="completed">
		<input type="checkbox" name="" checked>
		Hour of Code
	</li>
	<li class="completed">
		<input type="checkbox" name="">
		Post to Twitter
	</li>
	<li><input type="checkbox" name="">
	Update GitHub log
	</li>
</ul>

</body>
```

**Thoughts:** Today has been another very productive day so far. Colt Steele's lessons are very good, and I definitely enjoy having video content to learn from now. It seems like concepts are sticking better by being able to hear, watch, and participate opposed to solely reading and practicing. This was another good review for me as I lead up to the JavaScript section (why I really bought this course).

**Sidenote Jones:** Whenever I get the hiccups, they last for days (sometimes weeks). I've had the hiccups since yesterday, and it's the most irritating thing when trying to learn and practice anything. And yes, I've tried all of the methods. None of the ever work, but I'll take suggestions... Hmm, since this problem has not been solved for me, I guess I need to create a solution and app to take care of this. To the laboratory!

**Link to tweet:** [MightyJoeW Day 8](https://twitter.com/MightyJoeW/status/829472654885261312)


<h2 align="center">
Day 9: Thursday February 9, 2017 
</h2>  

**Today's Progress**: More Web Development Bootcamp CSS lessons plus additional work on Pokedex. Created pages for numerical list and alphabetical list.

<img src="https://lh3.googleusercontent.com/D29o-O-DE_xBXCVu_iHotMOrwIcOlfLVETINJ-sOgsVqISQp-jTYavzZ4nNORS1qQCVCegggdI5IINN-WinKpg0LK3JI_UujKdSDi_i7cNLqeQEu6gHZfYTGWV2tFPXCPrTFEdLX9MGgcQ6sWyg3LQhqhQOnETpYRCKEI2UZf33M55bKuU90Rx68biIDzVQcSPAJvNp4SQZibLn0AIZ6MVqmhMqswZyRxIQyS10sE0utpP_5KFKWd5x6mg3B6aT8jZHYr4b0uGnrdJmFyR2siClZZF3_Bx80dHrTX-W22LxdrVZPXoVcQKFsDkBmd13bAECiU07cMBh6-Fj2C3u1SZZn2qPcweSCImwfFBt0VxlrOv8K-hv3hqZkSZLn4HJKeKbcUTG4Ey2mQpXZnGdgIIt9Abao3xQ5xB9cjZbn0q67LQN_t9RkvIUH_f4rEwtKMK8pb5goCiRuylp_7enuIyK3DB2nWrCo7ymelKiEpH0mCtWXBEpV493R0SUL_IzThdebJILtBNKypRaK75daO0ahjyrXg7EWFiHdrc_HNQcojEab1j5eyPrxdk6V-htq08W4dgiY7Mgbw1ajvUi_Q1TBnXtT3HgL1iVstD-vjiIjiun55ZmRIA=w1186-h627-no" alt="Pokemon Table Code in Sublime Text">

**Thoughts:** Very tough day with flu-like symptoms, but made it an hour :cold_sweat:. 

**Link to tweet:** [MightyJoeW Day 9](https://twitter.com/MightyJoeW/status/829900574204256263)


<h2 align="center">
Day 10: Friday February 10, 2017 
</h2>  

**Today's Progress**: More work on the Pokedex. Hyperlinked the Number and Name titles to allow user to rearrange the Pokemon by number of name. 

```
<tr>
	<th><a href="#">Number</a></th>
	<th>Image</th>
	<th><a href="#">Name</a></th>
	<th>Type</th>
	<th>Evolves Into</th>
</tr>
```

Filled in more Pokemon info. Removed background photo. Also, created a [Pokemon Table Repository](https://github.com/MightyJoeW/The-Pokedex).

**Thoughts:** Still under the weather so today was mostly filling in information opposed to creating new things. 

**Link to tweet:** [MightyJoeW Day 10](https://twitter.com/MightyJoeW/status/830243763821895680)

**Link to work:** [Pokedex repository](https://github.com/MightyJoeW/The-Pokedex)


<h2 align="center">
Day 11: Saturday February 11, 2017 
</h2>


**Today's Progress**: Continued filling in Pokedex. Good amount of reps creating hrefs by scratch. 

```
<!-- Abra -->
<tr>
	<td>063</td>
	<td><img width=50 src="http://vignette2.wikia.nocookie.net/pokemon/images/6/62/063Abra.png/revision/latest/scale-to-width-down/200?cb=20140328202819"></td>
	<td><a href="http://pokemon.wikia.com/wiki/Abra" target="_blank">Abra</a></td>
	<td>Psychic</td>
	<td><a href="http://pokemon.wikia.com/wiki/Kadabra" target="_blank">Kadabra</a></td>
</tr>
<!-- Kadabra -->
<tr>
	<td>064</td>
	<td><img width=50 src="http://vignette2.wikia.nocookie.net/pokemon/images/9/97/064Kadabra.png/revision/latest/scale-to-width-down/200?cb=20140328202820&format=webp"></td>
	<td><a href="http://pokemon.wikia.com/wiki/Kadabra" target="_blank">Kadabra</a></td>
	<td>Psychic</td>
	<td><a href="http://pokemon.wikia.com/wiki/Alakazam" target="_blank">Alakazam</a></td>
</tr>
<!-- Alakazam -->
<tr>
	<td>065</td>
	<td><img width=50 src="http://vignette4.wikia.nocookie.net/pokemon/images/c/cc/065Alakazam.png/revision/latest/scale-to-width-down/200?cb=20140328202820"></td>
	<td><a href="http://pokemon.wikia.com/wiki/Alakazam" target="_blank">Alakazam</a></td>
	<td>Psychic</td>
	<td></td>
</tr>

```

<img src="https://lh3.googleusercontent.com/juOIwp32Uek9UsVmGFdY0G_jQpLN75BK75OJlsBixiMng01oVuGEcXT5ewhuKXt5ws3efz3ZXlyoywKGfUSY07f7EPnaxuaT1VuLW7aplW8SaJhxUHjT3JirqMnSBP74u2Jw7JYqpq577-0r_NJqI7U05oh6RMrfHuz5wzCBxxNIZAbxTpnpfLRFQqmE3bwqLm-1lhLeSpfUA3u0jP5x6KNH31YfT6xvG6soCQtWHqncNwZuRgXL-DMsbytyf6NpyyLaITa_uYXhGHIPZgSUZMYM_AxCqlwvN5QvIn_DQ9BqLoQDrX_lNDwNtJAq9ZT4xB-Dykt9P_ZX0P8vhINUq7GHDkWdGAlhdofCV3tIm_AcGlta_5zIalDmz-rCxeuvAxmOrr6MmkTuxx2HnlEIWwNthCdU_0i28Oa8ZFzA4aHs2JTnoZH6YyFXN1b_lRAupW6E_CrSCUwwl6NbsyVe1xeD0HczbhQ13OvZhD2aJh_nDSLOPZQh42WpCG3zWaTTVlho6NfUQ3z1x-R3t-pxjkfx6F5ko2KNs06mJ86UHVa0nMwglLAIWFARW64_CqXIOUjChb6kxZRzevYRbiIz7G2vdFcUV2VNiY6L7DXPpwXNoSGLGqxRnw=w1280-h179-no" alt="Abra, Kadabra, Alakazam">

**Thoughts:** Feeling better than yesterday (gettng over this sickness). I should be back in my regular zone tomorrow. 

**Link to tweet:** [MightyJoeW Day 11](https://twitter.com/MightyJoeW/status/830646204576968704)


<h2 align="center">
Day 12: Sunday February 12, 2017 
</h2> 

**Today's Progress**: Created a JavaScript quiz during today's Free Code Camp meetup. Also, continued filling out Pokedex. 

> Test your Javascript knowledge with my 5 question quiz [here](https://codepen.io/MightyJoeW/full/WOeOar/).

**Thoughts:** As we created the JavaScript quiz, I felt like a pro setting up the basic HTML and CSS sections. Then, JavaScript stepped in and kicked my butt! I understood the concepts, but I have a long way to go before I can create this kind of content on my own. The good thing is that it gets me more pumped and hungrier to keep pushing forward. Baby steps.

**Link to tweet:** [MightyJoeW Day 12](https://twitter.com/MightyJoeW/status/830989197112700929)

**Link to work:** [Simple JavaSCript Quiz](https://github.com/MightyJoeW/JavaScript-Quiz)


<h2 align="center">
Day 13: Monday February 13, 2017 
</h2>   

**Today's Progress**: Found error in my JavaScript quiz. ONE missing parenthesis messed up the whole code! Also, finally finished HTML section of Gen 1 Pokemon Chart.

<img src="https://lh3.googleusercontent.com/KI_GIoMuP_x9DPMEXB2Ttz37ZPuzpNop79E8GTnvt_dzVqX0Sc1bg0-SGV4cEXX7aZcSiwB0AnAt47zXCVx2JvSgZ0oeLqw2y0KUkO1K68PZossk5mteaz9rNtGRA6ufNiyfRAeTWV6xdBqzgnqlEdFTHtvDuiHBvbfGvzyiKmvtoeJAVI3k_MJEuQMH-GMBkUm7XBLYmPBSY8Xm1scvYKVgOVE3_BQRa4H33rAnC-2JaVGpgwTPCB8HFK2X6DW_tCBWOL3x5ptdOXnFM15GzSKaNPS29k4RU8SUdTRMGq2R7E0g91U5dV1jPoMR7_2Fem-esAcb4NQ7KnDDCGKzvQI8w14GiqnrzLo39Si1-0aslqHIxrI3Flgkd6OrMvncA6nxxpElOo7ZfcKCjqBHdTVrkQ6gXI4W0Sfd1Gp9DHr_LHfD5NCN1Sb1r5jBEu3R2h3gpGeEPbdssL5RjIAogpPT6f0BBaukfH03MNfDs0rzH0EOda1y1d13dPuKE8id5xC-38vf4u-DP_fzbdRW_iQ-FUaJ0oxaGpOfRkkI6RYu4xwA0HBSej7M9pEWsoeeDZHKehs4FbapbGKWRAtczenFcw0-cYr-lJovlXv9Rdbk9SavnSohzQ=w603-h296-no" alt="Bottom of Pokemon Chart">

**Thoughts:** Why did I choose something with 151 different character for an early table project? This took forever!! But I was determined to finish. I'm sure there was an easier way to input this information especially with some coding, and I look forward to implementing some changes in the future. I'd want to change the view from numerical to alphabetical without creating a second page and re-entering all of the data again. I'll be on the lookout for how to do this.  

**Link to tweet:** [MightyJoeW Day 13](https://twitter.com/MightyJoeW/status/831305975470628865)

**Link to repositories:** [Working JavaScript Quiz](https://github.com/MightyJoeW/JavaScript-Quiz), [Pokedex](https://github.com/MightyJoeW/The-Pokedex)


<h2 align="center">
Day 14: Tuesday February 14, 2017 
</h2>   

**Today's Progress**: Used JavaScript and the DOM tutorials to create webpages with various functionality. Completed CSS Selectors exercise in Udemy's Web Development Bootcamp course.

**Thoughts:**  Going off of DevTips' tutorials, I created a webpage that changes colors as you move the mouse around the page as well as a page that changes colors as the time changes. This was all pure JavaScript and still very confusing as the moment. This was recommended to prep for Sunday's Free Code Camp meetup, so I at least have been introduced to these concepts. 

[![JavaScript and the DOM](https://i.ytimg.com/vi/hM9h1wN4rfU/hqdefault.jpg?sqp=-oaymwEWCKgBEF5IWvKriqkDCQgBFQAAiEIYAQ==&rs=AOn4CLD0QG_jxhCT9c_DP465YMjqZ4WL8Q)](https://www.youtube.com/watch?v=hM9h1wN4rfU)

After a few days away from Udemy, I got back to those lessons and completed the CSS Selectors exercise. I feel like I have a pretty good early understanding of CSS, and I continue to be impressed with each new thing that I learn it can do. 

**Link to tweet:** [MightyJoeW Day 14](https://twitter.com/MightyJoeW/status/831675551203078144)


<h2 align="center">
Day 15: Wednesday February 15, 2017 
</h2> 

**Today's Progress**: Udemy lessons then created a CSS Tic Tac Toe board and a CSS blog from scratch.  

<img src="https://lh3.googleusercontent.com/cu518KsC4s2wESx9sSX_Wkrs8t__WdoFtzBM8vMVbuwVsGpHDSFgQKCuIy0ISW6vEFFm0chYyFgJ6r5OJTH0gk0rMB-msBpDtoMV9yTp2X_Wy6bzliP_s_KmprAwlog3Ig31cmfCSDoumDIOpgDWK59yB1tsWhXodBeyam9DQjGiXJhq1PVrQ3oa3crpNcv-SBqEkB2At5C73QSk9xEa_bLG2Pcd__TlMlk_mdAwOKwu7DQNFmin1vKu58x58pjm-_MReCOkT7FMVI8pzsMwFqpHjoKCsJh4Ecq1gepWy3tj9YE6nhi5l0dmedm_9n1USm7fYIl8TbdrL7EAV8EOT6Rx94Fpo8KkzF2oX1EYyxwk2t5CQbUPvy9fS-BFtI0V2gXYr7fh-ehfb6qUG_7znWxkipWP1GxOlqK7d2IvpAJuToP66jKYH8XSsiFweBOEatITQBS5KQET5gGm5_2it5vfa42zTZH1bwJriiZAQbQNjnV9ayaMxVOlBL0hI5rib6EVEwV42GqgDQpLkAE66y58ya6IG3OA4UzAYgNhKXoBh4A1zvbE5FrNDO-mq6Wkz9UcDYLS91RnSZtUbtC6b6lpGTOlCuUpaQ3V1lRg0Zywg10NdwLTvA=w1130-h627-no" alt="CSS Blog">

**Thoughts:** I couldn't be happier with my progress as well as my continued passion for learning how to code. I've hit a lot of different roadblocks along the way, but today showed me how much I've learned over the last couple of months. 

Since I had gotten stuck on multiple JavaScript challenges in Free Code Camp, I decided to find another resource to help me learn (enter Udemy's Web Development Bootcamp). Although I got the course for JavaScript, I thought it'd be a good idea to not jump ahead. I just completed the CSS section, and I felt extremely comfortable on all of the little projects. All of the reps and different classes definitely helped me grasp these concepts. 

Now, I'm hoping that this course can help these JavaScript concepts sink in more. I've been around JavaScript in SoloLearn, Free Code Camp, and various tutorials online, but it still feels over my head. It will be a marathon, and I'm prepared to **getScript('or Die Tryin')**. Let's do this!

**Link to tweet:** [MightyJoeW Day 15](https://twitter.com/MightyJoeW/status/832033261220196352)


<h2 align="center">
Day 16: Thursday February 16, 2017 
</h2> 

**Today's Progress**: FINALLY fixed navbar on portfolio to stay fixed at top (container needed to be ABOVE the navbar) 
. Also, fixed hamburger menu (needed to manually add bootstrap links from site opposed to using the quick links in codepen). Udemy course led me to finding this error.

Update 1: Never mind. Moving the container broke some other parts of the page (put whole page in a jumbotron and messed up the footer). Back to the drawing board!

Update 2: I found the error!!! A missing `</nav>`!!! I feel so relieved and frustrated at the same time lol. Great way to wrap up the night though :) 

<img src="https://lh3.googleusercontent.com/n7fgTZI930nf6CMjCieTm1Id73_TeeIfBadoAelRdhF--ETFRkaLAKMXEAIr0SuhdNDq3lIXQkHVVgy97adNdPEnlsR8qIE0Yos-sApXwj77Ly5y3T-AUlNfSO_cemRbU7kYR1GThXjW5dxhx-sZJChtNDwWdb_nVQ0aO2mSkqSQl4Lwo-opNRwlb9iApsg5tRxdAfbdElDHPy6F3cCbSEmZnATc6s3Kye0eebKIKI0TsNCT2vDpSn7bSZf_aQYSUSRSLfPwsYLPK_LEejGpzkgTnVLQCaFlkmCuliwQ0-hRDZtvjg2ex-Hc9HGeUgO5kzLtsSF9bxgU-pqhZKsQRhMDstGZDwKK0EWw7yqIulXeN2g6lLAecf5_bP57Wtk55HtRTjrYT-fGnkNNssoe4BtfP_UFu4yeTVHKP_lMjZshVDMOZ2UUcSVaDUUQNmG-4qODBCWK3GFtLRkwQXfuBQz2SNj-c1hoi7WhFJamyJBitQp674PbLmqEaSimaxBc67K8uTVsiqN4a4VqCRPLrcspPXWGbwBFxcN_TGZ0-tOPBb_1Uy57qZFDcL2CJNRSG3J5Rpakhp0aoE44CWiY3QI0THVKb0TaIR2Lx9bdE-Sa2TgFC08-Yw=w1213-h627-no" alt="Joe Warren Portfolio">

**Thoughts:** I'm thinking I may need to start from scratch with my portfolio. But I do feel like I can eventually figure out why the navbar will not work when fixed (and let's be honest, I don't want to start over from scratch lol).

It's been fun experimenting and getting different things to work, but unfortunately breaking things is a part of the process. I will figure this out. I will figure out how to have a fixed navbar and footer with everything in between displaying properly.

**Link to tweet:** [MightyJoeW Day 16](https://twitter.com/MightyJoeW/status/832394962432036868)

**Link to work:** [Portfolio](http://s.codepen.io/MightyJoeW/debug/JEEqNV/PNrvYLBOzOQM)


<h2 align="center">
Day 17: Friday February 17, 2017 
</h2> 

**Today's Progress**: 
- Finished HTML and CSS sections of Udemy's Web Development Bootcamp. 
- Adjusted columns on portfolio for different screen sizes (changed each to col-lg-3 col-med-3 col-sm-6). Also, started a new one from scratch since I'm still experiencing some issues.
- Created new landing page for one of my websites

**Thoughts:** 
- **Udemy** - I am thoroughly enjoying Udemy's Web Development Bootcamp course. Video lessons have been a great addition to my learning process. It's very helpful being able to see what someone is doing as well as hear explanations opposed to strictly reading. I am now to the JavaScript section, and I look forward to learning. Again, I bought this course specifically for help with JavaScript so I'm excited for another opportunity to learn this content. 

- **Portfolio** - The navbar was working properly, but the jumbotron engulfed the entire page. After being unsuccessful in figuring out where the issue was, I went through line-by-line (again) comparing to a solution from Web Development Bootcamp (which led to another issue of the navbar icons not showing up, but I found an updated font awesome link on StackOverflow that worked).

- **Landing Page** - When I first was introduced to Bootstrap, I didn't know what to think. It seemed too good to be true and almost like cheating. On Codepen, you simply click the Quickadd button, and you can then do all of these magical things. What has helped me understand Bootstrap a lot more was actually seeing the CSS file. I had no idea what the magic was before. Now, I can actually look through the CSS to see how everything works. It doesn't feel like cheating anymore because it's extremely intricate, you still need a deep understanding, and I can go in and edit things if needed. 

Using Bootstrap, I started working on a new landing page for one of my sites, gamesandkeys.com (video game piano tutorials, sheet music, and midi files). My focus is not currently on music and I haven't made any video game piano tutorials for awhile, but the site is still active and still gets traffic. I think I may keep going with this new version and do a complete overhaul. 

> Current GamesAndKeys.com Homepage (Blogger)

<img src="https://lh3.googleusercontent.com/Y9N7QSrKK59rrOd3frYCgZIZ69swdsfwymf_39NXV1yooZO24KSUyrLV-oyC-mmxnf3KtH7SBJiR5PJkmcHJoME8DhMyRt6xlDYyISJwn7IByea74upOTHSHeGgWb6bpeWv99PR7K2ox995pkSrqSnfnL35m1yMrUTkkrOBqHTbYyxaLikHyKp9xt_b9LyXukI835EwgDAGJG70o_KjmQcXLOko8PSoDoyNj0i4mg01uvMBHmq7nYDyJtdAlfvd8eVhq_L4KfkEEPeGLiCed0IHzT7gnfh9-PPvGMQrZzM5k2eSb7tYTxdaRwp01DUce5TkmYAdOa2nSV2xgjm5xWhPZP4Yyl5BdgiKkDWH6_JAgIj_QfiCyvn3VRevOlpUjEzkcJcArJTBPVOXaYLqknQkjeM7xNXVVg1IUwBCIXfS5GeBHoBz3OjNwlKaI2lUHGEJgWMnIPWIW0WkmKwWfAODnGGBYAXiR5pERR4ItMgONXO-Fmi4shLKvhf1fX1LpdHoq0HqKUut6gajmdFirAR4eSVlYl4bNsGtCSG5puarREu-iuCCaj6vPJc9BIXFb7gfIwL7aqqEYhwAUPkZGTRHILggYlSZEOsU16aW8BRLwWwgNjTkGlw=w1266-h597-no" alt="GamesAndKeys Blogger page">

> GamesAndKeys Landing Page concept

<img src="https://lh3.googleusercontent.com/4TqplbKaRs8I-Ysp04oY6Zy54NI6pXjN7soXB3Sx5DbMPb9c2VUoKnVt3MQA1vtQTyPhM0WbjZHgHxm3IN0aLQwW_6_DXEbDcXZZyPThmY5lgOD6fUrC6jBHllT2cACHo3Fz9HW73p3DpsnY9ycbX5GGAngQnOY5kJVps1t0sbnT6nh4zn7yABXC2dSMGs8BxN4TcD_HFKMDVVC5XBhfSjvWQ9k250Tjr63Ff_SMEzQFyf_lHnVh-tdNAl42D2J0xJgAsup9fkk4txmqpiMGSu3HsPZr94IheWFKzbfpXrEXFwBPGh072rkoWJzl6c1CXW-pPb88A58CTDHYvNd8ALy7k2E1UqngXN8iY-XJYoXOztHw9D748VHihY-MhcLZT3FyY7Nnj1Eu3FdpZc-XkBzuFTDC63a3rTRysGqJFTA9dgyANujckXXeweqDilthWEqZtt_i9p-FoNw1daCum59mO7MrthlzdY61Z1yDzTgHUxu8iCDY0j4MfeqrYwssAgcioJhEiapGy50s5gZ8rA_Km3cgmTdn6EBLPflkehMLYCoCNjZi9kNp8zTt8jpD8IlY-DCcKaPsaphJ5IflVb3g7W76NHQCugpukfl6A0GM4fi1jVdz6A=w1280-h626-no" alt="GamesAndKeys Blogger page">

**Sidenote Jones:** NBA Allstar Weekend!

**Link to tweet:** [MightyJoeW Day 17](https://twitter.com/MightyJoeW/status/832743411606179840)


<h2 align="center">
Day 18: Saturday February 18, 2017 
</h2>

**Today's Progress**: 
- Continued working on new portfolio page

**Thoughts:** 
- Not much done today as I was entertaining my nieces throughout the day :running:, but I made some good progress on my portfolio. It's coming along nicely.

**Link to tweet:** [MightyJoeW Day 18](https://twitter.com/MightyJoeW/status/833181935635726338)


<h2 align="center">
Day 19: Sunday February 19, 2017 
</h2>

**Today's Progress**: 
Worked in the DOM and with JavaScript at today's Free Code Camp meetup

**Thoughts:** 
I really enjoyed today's meetup (as I do each week). Today, we spent a lot of time discussing the DOM and practicing some JavaScript. One of the things I love most about being around others when learning are the little things that you pick up. Things are mentioned in passing that feel life changing lol. 

For example, I didn't know that text editors can rearrange your code to make it look better. In Sublime, highlight your code and go to Edit > Line > Reindent and voila, your code is cleaned up! I don't know the ins and outs of this or how reliable it is yet, but I will be utilizing this going forward.

<img src="https://lh3.googleusercontent.com/eOYQgZ7OEgUI_5a2im575xSWi_6G7kQkorYNOetpbu6qOlZr4C-iEs0V1GUNPlQ0w7QdfNWMfkVX5IHipwHnraMy4loAlg1B13pZT952dOb9EFzmdjxdR28OBQ7ksvoktR5aBjGF33bmmUESn3PmqLJw9XcR_PD_QGt8jmnm8_LgqCx4udw2SbQU0R-OS0WVGf23Z1W-oGTwmr2OC7-pKm9f4l9OIk0JJJaLV_kX0qskNGYkAke7V8PhiI46JPp8zwVwYFuySmeidSdL9a1G2BlHpnLE2VEW_QBZxNT10FLkGq7KeZnLOIDZlojxTKSxZw5LKGKcuXEctcdxuTToOfPstWmXs-UhB9EIhP8y_jsgYpxMJgri7CbWuFB-qdM2Knclvabu5i8e7VCdnsoXWP6oGAW3cbLMn1KfNqUZuYq3TrbDLns4nRDD_fm5g7-nXKr-cFOiSf6iJIi1k-fJbZLgDfulk1v1ROnU4-cKe7YGIgLFWc7gctbh6Q9taHt4asqEulIvgsFMJqQ9oShlVM-CanXsa83HzY9IeTg2YCp6Yw-yqyolBpMQNVxwQr5wUJ76yO0xbdZo4-WFUSHUPU6cCuRw_5oB_tQ8OWerEy9flhj8PDGMqg=w1280-h516-no" alt="Sublime Text Reindent">

**Link to tweet:** [MightyJoeW Day 19](https://twitter.com/MightyJoeW/status/833513634215124992)


<h2 align="center">
Day 20: Monday February 20, 2017 
</h2> 

**Today's Progress**: 
- Continued Udemy's Web Development Bootcamp lessons (working through JavaScript sections)
- Cleaned up codes with Sublime's Reindent feature 
- Reorganized programming folders/files

**Thoughts:** 
Today was another good day of learning and practicing. I'm working through the JavaScript section of my current course. I've learned a few new things, and have remembered things I've forgotten from weeks ago. I'm currently on the section about loops and working my way to the section about Objects (Objects is where I got stuck on Free Code Camp). 

**Link to tweet:** [MightyJoeW Day 20](https://twitter.com/MightyJoeW/status/833906812575481856)


<h2 align="center">
Day 21: Tuesday February 21, 2017 
</h2> 

**Today's Progress**: 
- Finished Udemy's Web Development Bootcamp Section 9: Javascript Basics: Control Flow. Up next: Section: 10 Javascript Basics: Functions
- Figured out what was wrong with my Portfolio thumbnail images (had to change the width and height in the links), centered text in jumbotron without adding effects of h1 and h3 (had to add div with text-center right before the text)

**Thoughts:** 
Another good day of learning and coding. I successfully wrote JavaScript code for various While Loops and For Loops. I remember first seeing JavaScript loops and thinking, "What in the world is with these i's and +'s."  Modulus makes a lot more sense now too. 

In regards to my portfolio, it's coming along. At the moment, I can't get my photo to appear on the right-side of my text (I had this working on my initial portfolio). I created a row and have my text as a col as well as my photo, so I just have to figure out what is missing or wrong. 

I also added photos and titles for projects I plan on completing including a JavaScript Drum Kit, a Simon game, and a Whack a Mole game. I look forward to diving into these projects in the near future.

Update: I figured it out!! Again, another small issue. I had the closing div tag AFTER my photo. I needed to change it to be above the photo. Now, the photo (which is a col), is showing up properly next to the text :smile:

**Link to tweet:** [MightyJoeW Day 21](https://twitter.com/MightyJoeW/status/834226942660505600)

**Link to work** [Joe Warren Portfolio](http://codepen.io/MightyJoeW/full/JEEqNV/)


<h2 align="center">
Day 22: Wednesday February 22, 2017 
</h2>

**Today's Progress**: 
- Practice with JavaScript functions
- HTML and CSS practice
- Continued work on Portfolio
- Finished Section 10: Javascript Basics: Functions


**Thoughts:** 
I actually had fun with functions this time around. I've done some JavaScript lessons before, but these videos are really helping this content sink in (the little quizzes are a good challenge too). I spent most of my coding time today going through the lessons. I do get distracted often created silly things with new things I've learned. 

I actually don't mind at this stage though because I'm seeing how much I'm retaining. I was supposed to make a basic html file and js file to do some js practice problems, but I found myself going into design mode trying to make the html and css look nice and pretty before starting the js problems lol. And, I still get a kick out of inspecting web pages and switching out the words to make it more amusing and ridiculous. Juvenile but for some reason hilarious to me.

> Sorry Github. But this is great practice :sweat_smile:

<img src="https://lh3.googleusercontent.com/wa-W9ZmRv9jYDyfsXjzcEm_0Gjl-g8715BzCaUQF8bJt0-Or9ovTo1Q3hV7ukcMzQa6XtV1KyPefkUawO0OLGjBM1rcHdeFsgFX3uruoVA0F0-GAww5Cu4ipqJvFZe5RKGSxMAO4Jvd9lYuIh8PTXqNzniJclgqUEQIhONkGrlEkIKt45SUhhTEZDUBmswminNrp73tsOSmVpXz6s2qpDJjUXRcl18uijjrBdPQBaBZRuyYA5FuFeyFOVRytaWrqM08QJBhzmfWRDW9nYouJWbiiMcS7xk0f2GVNyG5440UDlD-i6nUsSvkX-kszaBkyQf8_gYbDX0aYC3kDbV5p9srdAwAaqdGAgz1tIrPUVtEjCNR1h8S61Qe9alp6ma7hZh3W7RVPA1idb_l4SqR65QdHHKQF-MIKlj5bq6_wYL1f15aj3fGqrsf9dGzjSC5LtHKFg0zjlY3d4n7_Mx9a4MzlFYW7_D3V0xqRKS7jw7lkWj7Q_UXSexsgPigp7Duoj6mxA2ZjtoBJgQTnHPgJzyWfKrEQ02LsYofs9pqc_0ObiSztNpvWVCinfnQlb5Xc0nRjRSqqjqN0se6UZxW4MEOQ3wKSH_PktNB3GgWoCkp1iO6g_lBA_Q=w1265-h627-no" alt="Github Dookie Homepage">

**Edit Thursday 6-1-2017:** If you've never worked in the console on your browser to edit a page, right-click on the text that you want to change and click Inspect. It'll take you right to the html to make changes. The changes will only be visible on your browser, and will go away as soon as you leave or refresh the page, so have fun :thumbsup:

**Link to tweet:** [MightyJoeW Day 22](https://twitter.com/MightyJoeW/status/834624859422470144)

**Sidenote Jones** I just realized this doesn't have a spell check. Hopefully everything has been half-decent... :flushed:


<h2 align="center">
Day 23: Thursday February 23, 2017 
</h2>

**Today's Progress**: 
- JavaScript Arrays practice
- JavaScript forEach() lessons and practice
- Created array for Gen 1 Pokemon on my Pokedex (so each one can be indexed by number). Also, added bootstrap and began styling. 
- Added tweaks to portfolio

**Thoughts:** 
Today's JavaScript lessons (forEach) were a bit tricky. I'm feeling alright with 'while' and 'for' loops, but I'm a bit hazy on the forEach concept. I'll more than likely watch these videos again and get more practice tomorrow. 

Also, I'm ready to start making some apps! I was excited about the JavaScript 30 challenge weeks ago, but I quickly saw that I needed more JavaScript training. I'm itching to get started on the JavaScript Drum Kit. I may take another look at it next week.

<img src="http://tosbourn.com/img/javascript30-review.png" alt="#Javascript30">

**Link to tweet:** [MightyJoeW Day 23](https://twitter.com/MightyJoeW/status/835006956653920257)

**Sidenote Jones** 
I finally took advantage of this warm winter weather and went on a nice long bike ride earlier. It felt great but these legs are sore! (I've gotten sick a couple of times these past couple of months and my workout routine is all out of whack.)


<h2 align="center">
Day 24: Friday February 24, 2017 
</h2> 

**Today's Progress**:
- More Array Iteration practice using forEach()
- HTML and CSS tinkering

**Thoughts:** 
Array Iteration has not been my friend thus far. I'm currently trying to figure out an Array Problem Set.

**Link to tweet:** [MightyJoeW Day 24](https://twitter.com/MightyJoeW/status/835275665540788225)

**Sidenote Jones** 
The ‘coffee and code’ way of life is starting to make more sense. I’ve never been a consumer of coffee, but it’s been a few days in a row that I’ve gotten sleepy while trying to progress through this content. I may need to get a little taste of the coffee life :sleeping: #SleepyJones


<h2 align="center">
Day 25: Saturday February 25, 2017 
</h2> 

**Today's Progress**:
- Finished adding temporary thumbnails for each app/website on portfolio
- Started working on a new website for practice

**Thoughts:** 
I didn't do anything too deep today. I'm dog sitting for a buddy, and this pup is loaded with energy (Border Collie/Pit mix :dog:)! I managed to mess around with some HTML and bootstrap. I began to recreate a page I made years ago with Blogspot. 

Tomorrow, things will pick back up with the Free Code Camp meetup. They consistently keep us on our toes.

**Link to tweet:** [MightyJoeW Day 25](https://twitter.com/MightyJoeW/status/835729938149842944)


<h2 align="center">
Day 26: Sunday February 26, 2017 
</h2>

**Today's Progress**:
- Free Code Camp meetup (Discussed Wordpress & Git, Fetch API, and JavaScript Promises)
- Worked on JavaScript Array Problem Set
- Checked out some top ranked Portfolio's on Codepen

**Thoughts:** 
Today had a mix of many things. The content of today's Free Code Camp meetup was over my head, but it was still time well spent. Plus, someone that I was helping said "You know everything!" I literally said "Me?" and started laughing. Although I still feel so new to coding, I've come a long way and was very happy to be able to help and guide someone else. 

I spent some time at the end looking at one of the JS Array Problems, but I'll revisit this tomorrow with time and no distractions. 

Lastly, I still am wanting to make a cooler portfolio. I found some really good ones on Codepen and looked at some of their code. One of my favorites used SCSS which I want to learn in the near future. 

**Link to tweet:** [MightyJoeW Day 26](https://twitter.com/MightyJoeW/status/836024497346068480)


<h2 align="center">
Day 27: Monday February 27, 2017 
</h2>

**Today's Progress**:
- Installed Sass
- Worked on third edition of my portfolio

**Thoughts:** 
I messed around and got excited looking at portfolios on Codepen and started on yet another. The one I'm basing mine off of used all kinds of tools that I haven't seen before. Needless to say, I don't understand all of it, but it's fascinating!

<img src="https://lh3.googleusercontent.com/XnFs00uzOax_IZLd2I2ROgEd0N5Dh5gNy10y_LTwDRJA1LDWzizki6FM5aYSJWWH2SRZhCyg179MNfNketN1P5ekQQmO4C-NFg42KFSavvvie64UZ6XD3-JrukDYoKm4pef0Vk3BVMms_XCPPoejZ3R_0MkcKJHu-p8q3pLOUB0huhbiiTgeMdwhvM-AVmAuFTeSTnw_fRqcjHKMXmSrLP2KcCutZX-h6TysBm5sjQvs_FuIsDfLIfM1gnwKmQfGWAzGpqVoFKU6wka2O85iQlyvh3xoYhFcLFXisk9SXEsu0t-PCuKhUCGzhj56vJyvkAwPh56r2bSOQqhLAO0IPM1oxITgpciwgsAAZW4zJE9EwBXi4CTv3Sw7yHuon4csm9Y_a2QxV1UuUDXxjtSHaGowl0HL9m1nsdv_sA43l72Dig-DghCuFhs3uLRaY-KNNv5o8zZ_wUHQ47_lmreLH2K9k2bzS98ytURs1QIg65_vjYj0tDAOZHg36e2oJiQoH2sg1Egkqyn3-rW-_B8mc0WBaxj5P_AQqUq1yUQuCmmzvrvAJFtFiqeRp3Zin-ZwkbKa9FGNKHJcW14lorc2kqI41PaUUwL-SNGsE1YsxQourY4Yg9dIfw=w1278-h624-no" alt="Joe Warren Portfolio Deluxe">

**Link to tweet:** [MightyJoeW Day 27](https://twitter.com/MightyJoeW/status/836428525884309504)

**Link to work** [Joe Warren Portfolio Deluxe](http://s.codepen.io/MightyJoeW/debug/GWpKOm/wQMPoZoYwgnk) This portfolio is based off of MOHAMMED ERRAYSY's so I give him all of the credit. I'm learning from his code. Also, I haven't looked at the JavaScript yet, so I don't know if the Contact form is active (don't try it). 


<h2 align="center">
Day 28: Tuesday February 28, 2017 
</h2>

**Today's Progress**:
- Continued working on Portfolio: Deluxe Edition
- Checked out [The Odin Project](http://www.theodinproject.com/home)

**Thoughts:** 
The coding part of my day continued with my deluxe portfolio. I was going through the SCSS trying to see how much of it I could understand (same with the JS). The amount that was loaded into both is incredible. I get bits and pieces, but I look forward to having a better grasp of what exactly is going on.
Today’s learning came from The Odin Project. I had heard about it awhile ago on a podcast, and it was mentioned to me on Sunday. I thought it was only a Ruby program (it’s not), so I thought I’d take a look. Nearly 3 hours later, here I am in the trenches of another course! I learned some things I didn’t know about the Internet as well as some commands and shortcuts in the Command Line.

<img src="https://lh3.googleusercontent.com/YCMTMtWq9uYx7jj6w3yk9t4byuObsdY6iIym5z343TUnpIiPop4omEh6BJ4AWQMH3CAuQshA1S8gsTsMhXxO-NfEfmr8I0eAa3b5mcf9oVxTVJh_Kv48vesMeSmB4sNVkSGrLP-JwOMqz_BzKDvb1mJqAteHxRwSTZ4-2k9lf-f_fnfta4dOU_8Y1zBXe8Nz_tYG-nuTVgf_ofhqahicpo0kuHuZ9AGUiS72P1v4mxAYs4aAb_o5GWUKMV9fghLOBjePwH9j644XhXjed1RqWU5cfAqcWcJY1pPUhAmdGCEiUFjZVWKHhalHJRkMieCbLOPxpcEqAUzehrgnrwMsgcGnj4CvB0UIk1afWy6iEUuI6vGe9SyP2iuEwO-3KmA88tURizt03Kk4GhBqpWSfZt44BRkM6njp9547N2RyGu6UkMc421_8MOLgwh091oNIo4aWfPT2M33YqaJd8E4-oPY3WUTBpiH-cBoLelAaD-wsxwQYi3ZMPhMtdPWaWEYsLXW9sTE8iDIcdyCUv2bcAwwbQQgH_m1y1kXxveA44AIuqzYbxSiLGw0ZcWFubhelLX9ay3t6_KCHQm94ukCkzeraMRMn0muajAwcImfmtwk8ZNENoDrgHA=w1277-h445-no" alt="Command Line screenshot">

I am still committed to completing Free Code Camp, and I’m definitely going to keep going with The Web Development Bootcamp because that has explained everything so well, but I’m kind of feeling this Odin Project too. The good news is that I’m not on any timelines, and it doesn’t hurt learning from different sources. I’ve just got to make sure I’m focused overall and moving forward each day. 

**Link to tweet:** [MightyJoeW Day 28](https://twitter.com/MightyJoeW/status/836758789567152131)

**Link to work** [Joe Warren Portfolio Deluxe](http://s.codepen.io/MightyJoeW/debug/GWpKOm/wQMPoZoYwgnk) Again, this portfolio is based off of MOHAMMED ERRAYSY's.


<h2 align="center">Day 29: Wednesday March 1, 2017</h2>

**Today's Progress**:
- Odin project Command Line lessons
- Completed entire Railsbridge Installfest 
- Matrix Digital Rain in p5.js code along with Emily Xie

**Thoughts:** 
This will be short because I'm Sleepy Jones, but today was a really good day of unexpected progress. I continued going through the Odin project, and the Command Line now makes more sense to me than it ever has. I’ll try to use it regularly to get more comfortable with it. 

Then, I had a late night session coding along with Emily Xie’s Matrix [Digital Rain in p5.js tutorial](https://youtu.be/S1TQCi9axzg). Even though much of it was over my head, it was still fun and fascinating to code along with.

<img src="https://lh3.googleusercontent.com/fN5pZ7z1J7tWtvowjfyzI4itVpxtVyZWyUdgBYcNU-ux5WT58RMwImJ-tIWQaSCHmpZn2TFEWfBVfzJ7BcJ1Vd9K4EncghYMtk0taY83oeYDKYTBXvSnerfoCevSpAY5ZtCdmpoiBa7AIp5BDEw5WjQWeTWgfjhQYylNi3N77wSjnBlBbdq4IO0Bufquvi8y-JZL_pv57V3yze11i8qKQr76jzYBdkkg1mXteMw-ElWNl2_9jFgi3uuZG3rN4z1X4VNE3lID4HyNk6-1ukDN06cVJGF9pwPEBsrRamIFxPl8YcoBaoSddKEQ6OmuRoSLKXZRRct5DXy-1Wq-Rrg8nrpMyF2nYos3VACoXf9EDzPTdDpkgT7B-UzXsoo6AAenk_60xluV1uT1aoPwxwSS5Kfj-z8-Mc17fwHLnq2qKCC9Sw1Mw4wlOHA84wysp4bqywPiR1DSuz4sNk0ZMf-UUwsSAE6g9HM7pwg0onEFVTXAh-Tjp2cPrIwrOApXAVUYjbBMfxA_pIYOnKoXrmqV9UCpnyxcol7se_a7grra9sQ2y5Eaf4X0qEYNJTaegTJok6A7_4M1rksuAJ-WDaV087tcEin13FfEHrMWYlXbgmQu_ePEoadIPQ=w1145-h627-no" alt="Blue Matrix">

Sleeeeepy. Mighty Out. 

**Link to tweet:** [MightyJoeW Day 29](https://twitter.com/MightyJoeW/status/837188094176735232)

**Link to work:** [Blue Matrix](http://codepen.io/MightyJoeW/full/qrbJbL/) 


<h2 align="center">Day 30: Thursday March 2, 2017 </h2>

**Today's Progress**:
- Odin project Git and front-end dev sections

<img src="https://lh3.googleusercontent.com/kW3wBZRDg4aixpWkXh3vcFVDBs6xipAwDLABmNY8HxaTLpAPCdQqSYy1zJh9azvgxToP01kTP82I7vArcxCSHGk9UVv1M_u1aVXpHrxSmclVQckr1vLrf2gWzI1lEI4niAOcDXU8gu_ChiCHvTYc6rqmDuybUglBUS72H2qfJgRDBGa72lve18XEBnE-SQOS2ktCV-dyX1RMDONUHThrZQorSMtMD0CRnr1eWtMZxi1FFbt15tDeE0icS7aKsfCWSZic_P3UB9Nn8M7d_MbdxgFWx4P9vs8SbiVOzjfqJe5QOlQOYdS-AUQbKXefPDfx-NKwUE-LqzdE-07WH5h19pFqtSPyM9VNxgQXLH7OVDfe3HhqZBp2xf0eqNSK7PWUsHu4N750zQzWYKbXN8dcdiER-WXQEeaWbWqP_H7u9k_0V4G0y51Q818sjY9cFNxCdWEXDBKxcWuVkBjMJugpdXRck6iXZ3rM3a0ktdqjyS1GI1riNarU225yXmyt7Cc9ycz0fXpd-9JQlwgreQ2H0K-AFwzAfgawfTEDhkVFYR9dy7DS_lNPl8J98YecChdCuwPD5kAL2HH_sXj_mfYIAVdAGyC8RLnSnY3AKDnpZXFhzEhiB9I3Sw=w1278-h610-no" alt="Git">

**Thoughts:** 
I don't know if git takes awhile to get used to or The Odin Project is information overload, but git was wearing me out earlier! I do feel I have a much better understanding of it now though. Bottom line, it's going to take a lot of reps to get comfortable using git and the command line. 

<img src="https://lh3.googleusercontent.com/BqqW4-vBVH8T5Ik9laB3lpCsos9nPUn0DTbFtDiBsn0WFtlDzS2Lvf336kScQSkkYO6rdiUNLaG--K8k-F3dSlUttt5GW6zNTp0rowVgxg-7xnr91GXnuyw5c159dXSwZB_qFIuspSHAolECuNuejXlyev1cbjbpTNLRPYjluebNG2VpodvpqqyYqvPh5iworZv1g3BXVFGvGmxkCb6o4-XhSyOpCNn5YN01q9XCUbwpEpV8deZwgCMde-V0x3Pvw-f-Ieyq4lCzBLvcV3jfQvn_TPkTRHDXhqzDehlygPqHArD8eJfMSHK26vIi995rQn9Bx9rvS_VBdRYREYkWVFg0dfZoRZLy3q1bsfzxOhNSQ7oG125RXYYwAxeekCWzzd-3ZwJfU9pOwTEUTDu0mGzImkOy63hM6fpifneayPwjFvwGpSjmwN_Zv1dKoFehlY1kA_Nf7Fx2u9h6IMGRgMjGqNkNwCmrJbfS0saaP_Kf-gug0OjFh_CpIMQFHxwgY7TOQ8lhhcoGWGxqQ2j9wjeCE_PUL-hQwV1ohddgyoxymORqqSFByrO3PQ0AOees0bdarRWCgWYD2NFkGnWw-tLLyhcMROcycPQ-8qe_2y5K6V915LFyfg=w1147-h627-no" alt="What is the Command Line?">

**Link to tweet:** [MightyJoeW Day 30](https://twitter.com/MightyJoeW/status/837531166001410049)

**Sidenote Jones** 
I never knew about Google's Revision history. This can come in handy big time.


<h2 align="center">Day 31: Friday March 3, 2017</h2>

**Today's Progress**:
- More Odin Project HTML and CSS work

**Thoughts:** 
 Another day with mostly review, but I have been picking up new little things with both HTML and CSS.

**Link to tweet:** [MightyJoeW Day 31](https://twitter.com/MightyJoeW/status/837863066066948096)

**Sidenote Jones** 
I'm both Hungry Jones and Sleepy Jones right now. I need food and a bed. Goodnight!


<h2 align="center">Day 32: Saturday March 4, 2017</h2>

**Today's Progress**:
- More Odin Project HTML and CSS work (focused more on CSS)

**Thoughts:** 
After a long day of driving (ROAD TRIP!!) and seeing family, I am definitely ready to dive into bed. However, I do NOT want to break my streak. Day 32, and I'm just getting warmed up! I just spent an hour continuing the Odin Project (I'm currently in the [HTML & CSS Codecademy section](https://www.codecademy.com/learn/web)). 

<img src="https://lh3.googleusercontent.com/YItitKjtF6UKzszD5wZ80DMjOXUI8IqcHL9tJuASdwV0Lqk0utLrvgkOHAQRBfoA3fhJaPR-pu6FNMm_aA7SkjulVATBYSCv32DjgAfPgtUxAMVIoeHWSWbAeRexJUBfoJ5U9HQSfalE9fNvoFC2VxsxULLOSS6JytgCRzeuP1itE1UHR7UTjjswyh_7MaO2Z461Eb10y_KYqGCOK_ZmzAj3vgFR-l5SP_zWvTb-No1Hqi3ozHhsbX8PaafTjjoCxQRsq2Haxj1anOGFeiYeusvPcXbJcLYle65nC10b1uL1H-8aH0at7mnGHPteS9OawP3NZKlgGS9ZV0bwAdNLbDVMHF-I4BCO5pu-LmYfL_rxq0SuH7xQT85Oe6O1CC5FQC59cBBh23u3yx1okMNjPIf7rI5X0rUukCLlHG3HvEmXCyehxtSxeUIAgT_8M0ELup_NQPZQry9B0U25QxaIFog9XgWUkcTyRwPvl-brZnVPTlHG1sDXMaWeAPreDcAMZiDwXtnw3YfX3T9-ycKXtUFCCpvl0_d1dZhmj1ScSr59HkTTUidsIpXA1qRR-jfbNMWzjRMpZbD_vN-H2eRYwGDdJCahO4KBIiKjWJEdOxvMglwLdx6C7w=w1219-h627-no" alt="Codecademy HTML and CSS">

This is mostly review, but I had forgotten all about the pseudo-classes in CSS. This was a good opportunity for me to get some more reps with this. A couple that I used were X:first-child{} and X:nth-child(n){}. In the Udemy course that I'm also working through (Web Development Bootcamp), he shared this helpful link with [30 important CSS Selectors](https://code.tutsplus.com/tutorials/the-30-css-selectors-you-must-memorize--net-16048).

<img src="https://lh3.googleusercontent.com/YHcG33l1hA3GY6TmY3Tuo5lFC4ljJqpD6VeP6L77NXJBb_ISvsUTJuZdX_gsUUlEtYGLmKI-Ke5d_iqcxKJ2o6t5cueIDR1y_uk8JlO9bLUR98Dz4a0Vk8k4t57P9eBiszoCaPzsZK1DAX54-cNZOGUfaEgi8EQqhnNeteQjcMz1AHrWrrUYzR2ACn1l2YJyYuFzdgbl-sQjYwCthYIsceDSQ8uFITTlKknSicgpYvf8oOTA5Z59Y4ddT2ayYCpOv4EcPGUfhNhHLUowhnYnn1Y0eX2_5ispV3F7i_GJ2T-r0YwRWyUpIRPNSN0EUdJgiPhAa4tNLevGes6ExGt45_SH7s4O0GfXmbvDhOCpCErMtKS0uWnEKx24cAPwUkdg8ZDfd5csMqHyc8BXn6LK8P9hxo1gptubwG87hiPh4XVbeHUyvxnoO1JEnzk6lreUOneSbElGX75kle3QdUMXhVNByOb_208vcld6rbSbm3Om1g5Nz_vvh6F3y3jeFPeLAI8kE3hmUEOEbmRXqAyL_ytUkcPcMe8L63Fd74cqC4mHbxRtPMwpVOwbsFIX7bBlGyXkJcziQ3NkyvOvmxk98Fdr6aXNdK3APHKn0-ouz_8mISbtQ1yUaQ=w387-h295-no" alt="CSS Selector">

**Link to tweet:** [MightyJoeW Day 32](https://twitter.com/MightyJoeW/status/838281454945767424)

**Sidenote Jones** 
I really need to start writing these updates earlier in the day. I usually write this right before going to bed, and I'm about a half second away from dozing off and crashing my head right through my computer screen. I'm really not in the mood to go to the hospital or buy a new laptop (well, I am currently working on an old 2009 Macbook so that wouldn't be the worst idea...). Yeah, time for bed... Goodnight!


<h2 align="center">Day 33: Sunday March 5, 2017</h2>

**Today's Progress**:
- Continued CSS section of Codecademy for Odin Project

**Thoughts:** 
Today's work was a quick hour working with CSS. It was a great refresher since I had been focusing on Javascript for the past month or so. Specifically, it was good to get in some more reps with simple things such as block, inline-block, inline, none, floats, and clear. I was also able to get some more reps in with positioning. 

**Link to tweet:** [MightyJoeW Day 33](https://twitter.com/MightyJoeW/status/838642454924505089)

**Sidenote Jones** 
I spent most of yesterday with family I hadn't seen in awhile, and we had a great time. At the end of the night, we decided to put on a movie. We were met with the usual Netflix dilemma of “What should we watch?” I was very vocal about not wanting to pick since I watch movies the least, but somehow I ended up picking. 

I had been wanting to see I.T. because the concept of some hacker taking over a smarthome intrigued me. I mentioned it but didn’t want to be responsible for provided everyone with two hours that they couldn’t get back if it was terrible or too technical. They were interested and fired it up. 

<img src="http://photo.elcinema.com.s3.amazonaws.com/uploads/_315x420_a52e97853a3486c7b37600a409d3030b95652ab90a1427c0818f1d8b5a97582e.jpg" alt="I.T. Movie Poster">

The concept was good, but unfortunately the movie felt flat. Also, it was another source of entertainment that portrayed programmers (or hackers) as sick and sadistic people that hide in the shadows ruining people’s lives which kinda sucks as I was just telling everyone how I've gotten into coding... Darn you Hollywood! 


<h2 align="center">Day 34: Monday March 6, 2017</h2>

**Today's Progress**:
- Finished CSS section of Odin Project
- Played CodeCombat with JavaScript as my language of choice

**Thoughts:** 
I'm near the end of the CSS section of the Odin Project. I ended the night following along with The Code Player to create an animated Android Logo with CSS. 

I'm looking forward to the JavaScript section. I’m planning to work through the Free Code Camp, Web Development Bootcamp, and Odin Project JavaScript sections together to help reinforce various concepts. 

Smooth segway to CodeCombat. I wanted to get a feel of CodeCombat to see if this was a good resource for kids to learn how to code, and I am very impressed. You can pick from a few different programming languages to use as commands to control your character. For example, one of the levels is a maze in which your character needs to go right, then up, then right, then down multiple times. With JavaScript as your language of choice, you can use a while loop like this:

```
while(true) {
    hero.moveRight();
    hero.moveUp();
    hero.moveRight();
    hero.moveDown();
}
```

The syntax is authentic, and the process feels true to coding although it doesn’t feel like coding (it really feels like playing a video game). Looks like I better replace some Pokemon Moon time with CodeCombat. 

<img src="https://lh3.googleusercontent.com/uj_mZO2KRdTAVRredKYzb_zPh6EjaXv3GVUjkLaPxAOXBS66UtbGMensGMNrJIyh6oDPgIf15s9dF0iSo73fEoS6RJSCkOsSs1wJd-EgnzN9LcNJEjZy0b_e7ts1Agga4iZHJrOr9xclsjhpOpacU0S2IePWNEjQUww6vYqUo3gaOkdgkbJ_uFODqTBEOZHFTzY-GkvAScW-2yZtebNQLLIlOAfjynWQ7Zv5iHJ4GLWGv5zLz6g8VXQCekEMQW6slGggQt9yn-6UXH6n-HRMxQiX6w6wglZT_CGCnMr0y4oSkKWmUJNgHSAn07vavk-dxLThWkZLPgqRFObdUDSqVq6S4ByuBNOSl_1shkNHqceWyV2OiDoMDO9EEiI0f5lTZVOWKaM8h-lt6OyPohJeILf7ATp3axocasmsPX0I4Prqipm-ZG4YHiTcziQECaDKk_4_rO8H1-76pu9ZeVoXNQlDNcK7_n_xWkh3I835_qV5PP_lxaLBRkWwVE-qy60mYSfHTylGGJGzAbRU3kR6ze8ualaWw1vHpZt3TS1JIcozs7kJhA46LsFy3DR2deRVvcH6lTE4rNU_aItCiVdF8zsbNXqwXpPidpGKSf59LccJme_TCrbEcA=w1278-h696-no" alt="Code Combat">

**Link to Work:** [Android Logo](http://codepen.io/MightyJoeW/full/oZzreR/)

**Link to tweet:** [MightyJoeW Day 34](https://twitter.com/MightyJoeW/status/839016634174029824)


<h2 align="center">Day 35: Tuesday March 7, 2017</h2>

**Today's Progress**:
- Odin Project - Developer Tools
- CodeCombat

**Thoughts:** 
I’ve been using Chrome’s DevTools for the last few months and have felt pretty comfortable with it, but I’ve learn a lot of new things that it can do today. Odin’s Project led to various articles and videos walking through what all you can do with HTML, CSS, and JavaScript with the DevTools. I only knew the basics, so I’ll list a few things that I picked up.


* **HTML** - In Elements, you can right-click on a line and choose Edit as HTML. Also, you can drag a line to move it somewhere else.

<img src="https://lh3.googleusercontent.com/Z29d2v84eGvBfKiXuvHzEuuGt6XaSOgZRBewtZW-oJvhKm5Y5WHAXPdebbiPh3hCmhI3xySrW1cWNl_aOELu_BrsOH-SapimyH9GGtiAZzkHvvRCPilHH0tH8APuIFJXBKoucbX2KXxiZI0FiusnCcleOUpM3fm1YZdpdv-85XPbwH1VTyGRIqI4bv_XhzERrIx38CoGT5A_71sHbSOdPgdYqWFJl9zj7VId0AbaqdXuf16_NoeNL0HdZH3WfHgAOJKEJvC5E3jNRGp-J0Zh-kQxtqJ1-MZIVxFirCayGd2Pr-NK86suExav0MYJEHGYE6t7tnco9roiXscJ93yPETgbnhO7OxyTvXkNeL5E7wj66L9Gj8YITY71u2L_JayaiWrtH12Uk2evJxh_Uef_iropoY9NR2zJlSuL4z8eNERKSF-FW8Tkok9rjRBorPgFPOwGfVNAs3J-XTdVjehINACnBQm6CIQsT2wBktlmBRvRNRZiK6HjqxQvvHOhpgFiSXCdmDhzNE8BpQRLa9Tw2jVjkLkj5OH45NyrDpcI-8QGCE-VqTHPMlY0doj9cZO0NQj4zFJYA7gjcYkOJ7XVObLa6qkEBQbAACc3PrZHtMUYqn-b6_bzmw=w1273-h689-no" alt="Edit HTML in Console">

* **CSS** - You can click the plus button at top right to add a new style rule. Clicking :hov allows you to choose a hover state to edit
* **Sources** - allow you to edit the site's files (but it saves it to our browser storage, not the original file)
* **Network** - throttling allows you to change connection speed to test a site’s performance

Next up is Project: HTML/CSS. Then, I'll be in the JavaScript section of the Odin Project. 

**Link to tweet:** [MightyJoeW Day 35](https://twitter.com/MightyJoeW/status/839353199307948033)

**Sidenote Jones** 
The DevTools things that I picked up today were immediately helpful, and I found myself spending a lot of time going through different sites and trying these out. After I had enough practice with these new things, I got back to one of my favorite pass times: simply editing words on serious sites to make it as sophomoric and juvenile as possible! I don't know why it's so funny, but I crack myself up :D


<h2 align="center">Day 36: Wednesday March 8, 2017</h2>

**Today's Progress**:
- Project: HTML/CSS (recreate Google Homepage)

**Thoughts:** 
I was challenged to recreate Google’s homepage within the first few weeks of my coding journey (December 2016), so this will be a good opportunity to finish my original attempt. There were multiple things off with the header and the footer, so we’ll see if I can fix them. 

**Link to tweet:** [MightyJoeW Day 36](https://twitter.com/MightyJoeW/status/839733793258946560)


<h2 align="center">Day 37: Thursday March 9, 2017</h2>

**Today's Progress**:
- Project: HTML/CSS (recreate Google Homepage)

**Thoughts:** 
The Google page is coming along well. There are a few little things I can’t figure out positioning-wise (specifically lining up everything in the header), and I still need to fix and finish the footer. 

**Link to tweet:** [MightyJoeW Day 37](https://twitter.com/MightyJoeW/status/839998100404076544)

**Link to work** [Google Homepage](http://codepen.io/MightyJoeW/full/qrraWL/)

**Sidenote Jones** 
So, I finally watched a couple of episodes of Silicon Valley and I'm pretty sure I'm hooked already.

<img src="http://www.shinedown.com/sites/g/files/g2000005191/f/fhfhfh_16.jpg" alt="Silicon Valley poster">


<h2 align="center">Day 38: Friday March 10, 2017</h2>

**Today's Progress**:
- Finished Project: HTML/CSS (recreate Google Homepage)
- Started Javascript section of the Odin Project

**Thoughts:** 
Wow, so I'm updating this post a day later and I copy & pasted my link below to look at my Google replica and thought, "Shoot, I must have copied the wrong link because just Google popped up..." It quickly dawned on me that my project was a Google replica, so I am proud of myself that I fooled myself lol. 

<img src="https://lh3.googleusercontent.com/WL3reD1U3s9_XyDgI-9Hv0UceX6I4iQjZb3JCDaj68l273twyLWQpyFD1cfNZVI5QtD2aLJoIl1P-GwbN61Izo6O28v0T2dfQVE0MmDo1J1YXIeT033vfrCDVJ9DQXDLzR8R-P0w720YLizV4sPkT4KcJgXqi4zApWcdl2QTpUe-v5iFiS77zLS3IWju76pKMy78bZik4QEpQJzm0iRkraEyv8UB530hNwmxK-ijdhLXaLk2dozNGu9lPleGrctcUSTbvip0V5u7EXfGkzUBjcf_z08gqkFosBp-wtYNfbrAnYZfEDXjwhY-B9pe-AObGbb1sjRDzuICO8nP_tc6dJLAw6ZsVRrO6IcwyRWqKCiE59C8BEBeQRHHAFADfC9KDSy3OJUXJaADb-nO0Z_gKSX4JiSNZhHO9654hbtTuv-5dvdaxBMLXFvcBuS1fzXu88p44C1VBWEfIZYmv1RYg_BScUQWUF228akotJNsDXO0T758Mb5e0Ms2uNhSCa-1ID1lvUEwq19B6X3UkX9aF8_FZe4IfkoaNEnocxiE3kSqbx0Gj5zefeDMsiZqTGrL-XXUVyTaviAt--SlECItxbHFbhYeRzj6inZE6hOPGJ2Bekg9F4VNwA=w539-h296-no" alt="Google Replica">

The replica is not identical (i.e. the header is not aligned the same way, the buttons look a bit different), but I’m very happy with it for now. I may revisit this in the future for a third attempt to see if I can get everything exactly the same. 

After finishing, I hopped into the Javascript section (which starts off with a Codecademy course). It always feels good to fly through early sections of a course. Hopefully, the copious resources that the Odin Project provides will get me to that next level with Javascript. 

**Link to tweet:** [MightyJoeW Day 38](https://twitter.com/MightyJoeW/status/840357122089070592)

**Link to work** [Google Homepage](https://mightyjoew.github.io/google-homepage/)

**Sidenote Jones** 
I'm truly considering applying to speak at this summer's AlterConf. They tweeted "AlterConf is looking for marginalized ppl in tech/gaming for paid speaking opportunities. No experience necessary!" 

It's in August, so I have plenty of time to come up with material.


<h2 align="center">Day 39: Saturday March 11, 2017</h2>

**Today's Progress**:
- Built Rock Paper Scissors game with JavaScript

**Thoughts:** 
 After completing a quick Rock, Paper Scissors Javascript game, @HBoutrup suggested that nothing beats The Rock (which gave me an idea...) :D
 
 <img src="https://lh3.googleusercontent.com/Xc_Hs8pvojwxuev0ytoDQwRgRDg2aHns9xE3eTbOLmZOTqs6B0UXf7tmCJkmAfYqVe7TLxtqvS-RMYXloRE9i0kxP8100XjGz_OjcPMZDIEtWLs0kiNyvUKVBipCSfk9zaCc4dSEuSzdq4_PzlX7b3pWSHpm1SsLwabxKHYrcjQZR33GR3YfBkJ8fzrBqcIdNghcj20mZ-AAAKvLdza6oJ5KCbEj1qBIiCk7vcb9RoJ7zFkSYlGJuvWdzvyrg70MHrvLaf9c1xf-fPEhwSneckmOVKw5XwzwphFSjfVGQ6gxdCzzXmeEt1ltHVs-xLcHr0fr4n7chUHpTQfq2rArxtmvznRgErZ80xG-NlGu_3OMJTOdOCvb93F86wYSwhUIcdtC9V0JZkT9ZnbpJU-OS2PRb_o6LEyM9A7_JFIj86OJmyKqq8O_7q4wTZZ1CO_cLk4jBiPjET2KlcYcvsvJzTZklmNi9nhgywL1HnvXHpwEpCS3dHS2GztRwfovHqY7-u31K6fkMOLki-1b0_4FVdELwDYfFopYnCEILORE2PrDpHnD26Nt00n-JAoTG0JhvrdCi4wO-rMP9KC_W8a33fs-qryVQMaXB-TjzTJNMN9FO7Sae5fuLw=w1270-h703-no" alt="ROCK paper scissors tweet">

**Link to tweet:** [MightyJoeW Day 39](https://twitter.com/MightyJoeW/status/840660850289586181)


<h2 align="center">Day 40: Sunday March 12, 2017</h2>

**Today's Progress**:
- Free Code Camp meetup
- Worked on HEEL Rock, Paper, Scissors

**Thoughts:** 
Today was a fun day of coding. At Free Code Camp, we used Kahoot to do a 20 question JavaScript quiz. I started off whoopin’ butt, but then the 20 second timer whooped me during the functions questions. It was good and fun opportunity to think quickly & work under pressure. I finished 8th out of 20-something, but I want that **number 1 spot**.

<img src="https://lh3.googleusercontent.com/78OIWkjrnDvNkQ1u1raXgILuY63fadGQWVE2Vv1LcvoYIKJXp7-JdHvfl_KhMWyhSf_vHKB09URPzHZZDWhE2J_50uG8_9B393-OXMpYWmWOItHlqS01S_5fDC26TWX66QRA4HjZ9upgW9yitgushmENiv6ZySRAzKkshlqbtTrrgxCM9ykiaMIvrErKDfHwJDwy-P2Zq1DLWKeDS-uYmYVbVIM5D2HxpWLmdMXdNtuHnKHfdSNdCFggY0jyESVYgD49PNa2GS0bus0sjbs-eMg-AFWvnqCtvBdvGz-wslb1Knb6Wf1m5ekx5tQZXZIQr-16lsbSNoJaKlAiAPw5iVnFMO4YPJECO_IF304zQCu0HVa2Tt_eOY5QKPWR4YU8EhuqQbIl35Uovj85LCA-isUY8xBA5vnr_KUmHnKuiffap7nejOLiwm0EPAqmX9MfVGvuctbntRxzXF83dglUGMU8B6dy78qrpn82fi4zUb2dr8ZRF75515TmmBsrdoaZm26lZCgfRFFcJKlby8I2IzMdgx-vwPVeWkdEWwYbV6jYBFnE3CAy1gnvtGyPkelsGfsdNUwy4YlezkJFnEch0aF6_gAt9A4qddoitEkkH8YjjI_itUmPXw=w186-h165-no" alt="Kahoot Javascript challenge">

I spent the rest of the time working on my HEEL Rock Paper Scissors game. Shoutout to @HBoutrup for the idea. He made a joke about The Rock being unbeatable, so I thought it’d be funny to base my game off of that concept instead of the usual rules. 

<img src="https://lh3.googleusercontent.com/KulTGzwK0nOQoPNQ48PKbGOmD7lwMkJapw4Z4bdTwRyC0sJbRVrppvNcnEWDhjZSDS4zllza4W6MPk9sC98qH6__y4m-E4I72aRW2HKAXjee1DDNyB_bRldvcl0jKDspmShxYl1wcK_bEFIUfp0dc0VVntzABP_hJq8xGknwC3tYxh_9dLnK5CHJpw-bn0QVMBS3q32YmGlrUv5MkJc2AKMUNOqrwZgKqiXu5DZ9SWxeHxGMxST4Zu3xW2IqrMoh3rZHb4vk94Ck1XGE1urlZ9o-isADBb7Jq_SJnmK4E7-tiNrvYQkITJACNwXVAoa_5G6U-mMuWXlBrWits_35OeQ4hi3bdVHmG4ns3Vf6ZU6xDIKxl_4rG57Lr2BmMSHXSSwNo6w0Q9T7iI7GArmRCW19Y7gzlskQswymaHqc_bmOOqwuIXiwNUaIr4njeyB-6DimWl3LyK0OEUj-ZKR7uDZ7b2CQ63w4pmu5ZObey_ENAt9_tdjfu6IxjEaa4hk3Wj_6UE4xN_AuPrFvG86MTlW1mpszJ0xAWQHjDoNON1l2nQnN7YorWcyBMY5v-Yzm3PJzc6KvkBkEUQDg754FSLSt2QzjZVNoFVVK144HGjl3RR2_LhKdEA=w1278-h321-no" alt="HEEL Rock Paper Scissors logo">

On a technical level, I’m having trouble getting everything connected. I feel like I’m missing some little bitty piece and just can’t yet figure out what it is. When using a prompt to get the user’s choice, everything is working fine. However, when trying to use a button onclick, the results are opened on a new page. I will figure this out.

**Link to tweet:** [MightyJoeW Day 40](https://twitter.com/MightyJoeW/status/841143742958567424)

**Link to work** [HEEL Rock Paper Scissors](https://mightyjoew.github.io/HeelRockPS/)


<h2 align="center">Day 41: Monday March 13, 2017</h2>

**Today's Progress**:
- Added changes to HEEL Rock, Paper, Scissors

<img src="https://lh3.googleusercontent.com/bdKpZVWB7yLpYW4fe5MJOsSO8eMQttF-d4n44zKTzwjfcCkvbsFSOJa5g8_YUyh_vJvBbytEXCtHegjTPqD1I4FWqqWfka9fnIhOqQFPoUcDoTf0VIkGgxqKKqZi_th5tcrPd3WFwBoONGqK9FaPo88pdxCKAEbBZ5-HnC4E6E8-UZYglH7HZnCjzKzoymQWBLnLys1zUmWpEpt1KcLTTcr3Xj56L6FFIoxe6DcMKU2K8h1yIiY8fa3Gm9My-OeHQaRU6m-EUg4FObkIlbAXp2CgkytXXG4Bj0O1nIB0svV4GCssU-NOpS4oWHv1CLl4TRstkREZzRdc0kohgadasvXy-l3SwOliU4O7RJ6HvF5YxU_df4ElkWk7xpY5sncb4MSeCMixVFTwauzh9Nr3IvzrdyuVc5s08GQBz_Mhk2pHzSq1xCkmQa20IrL-Oir3mgRdqHvBrXpbMao4cBjLsSSM2MGxb6gcxwQu8nYQiF5CH4ThhJcCAZOOhtY4a-xDWveWSvVABgVgutO-EtUAmNapnjUpggUQ8UMq0mH4Le3Vd4pZXDWgG6zHfsyYryEVoZYHJKVB_lYeiu8Fmwc9-Ejm-fRbKxZa5hrI3_l2n03OpeFYCtLvlA=w537-h295-no" alt="HEEL RPS early">

**Thoughts:** 
I didn't spend as much time coding today as usual, but I made some good progress on HEEL Rock, Paper, Scissors today. By tomorrow, I think I'll have a newly designed and playable game :)

**Link to tweet:** [MightyJoeW Day 41](https://twitter.com/MightyJoeW/status/841501322708963328)


<h2 align="center">Day 42: Tuesday March 14, 2017</h2>

**Today's Progress**:
- Finished HEEL Rock Paper Scissors 2.0

**Thoughts:** 
Wow, it is finished and I am happy! HUGE shoutout to [steveszc](https://codepen.io/steveszc/). My original Rock Paper Scissors was not functional (and not pretty). I was able to use his version to learn how to get everything functioning and laid out much better. 

<img src="https://lh3.googleusercontent.com/ELQBHyboW7KeNDV0PjM6ycGGl3NeWfQAZ_zHMrHpdlCAEEXqRwSzQaZZgTtyW2hx7fXlv6jQANtDChW15lYivqQdj243AA5BwgZaV-12xW0oBXxun1bTXUtIIMamBEseA_WYFiq-nPGREiRlChApHuxlhQR9WQ6sEl4C6qB4KO9GazqE-oQ2Tgh3M80tKrp4zmkl9d1XWpEKrwk7PrNhYJFmlRleLSOSczTFlGs3wBgai59eCj-h64c3JY_Z7r16GrlwUSZpRdl6NpXF4Hdhzyw2wYFPHEjpUdObUXnZd46f4wAIUPXz7l0PaiJMsSYi7WhdGCHd04QhOH-ywWxAvDdJdUyU5OVfna5Lu6tEcaVxiYd_E60YN-oULRNNi7V7kTM1DvneY1DJXv1LUmkoAo8x0KYbs3MNjHHrMkT-jQBh5hLJsbwY3eWAvGttfJxr9rGZl0tSp5A5h3owEzBghOIhxHnct8PTsd2gfE0fl87D4YeYx4fr-IdLIa3bik4-l2flcApHwUzFQNq9t70Rb7idDsxT_3Dg0YOyOPOLw2K0CgQb6LkxyyKDetzITsPXq5R66maJU1ZZDzefUHHVaVHHwPLpFoXmi-1enQ9ZYn7Rq40HZSiShA=w1152-h627-no" alt="HEEL Rock Paper Scissors">

I was able to experience what others mean when they said to just code and to learn from other people's code. I've been doing a lot of lessons, but it was very helpful having to experiment & Google, and also being able to see how the code looks of what I was actually striving for. There are a lot of little things you pick up that may not be covered in whatever lesson you are completing. 

**Link to tweet:** [MightyJoeW Day 42](https://twitter.com/MightyJoeW/status/841727679607013377)


<h2 align="center">Day 43: Wednesday March 15, 2017</h2>

**Today's Progress**:
- Continued Odin project (Codecademy's Javascript Sections 1-5 and the Codecademy Choose-Your-Own-Adventure Project)

**Thoughts:** 
I experienced my first browser crash creating while loops. It took me a minute to realize what was happening. Once the lightbulb came on, I was like "OOOOH, this is what Codecademy warned me about with infinite loops!" Then, I was able to find what I had done wrong. 
 
I wrapped up today's work with a [Choose Your Own Adventure game](https://repl.it/GXrA/0) which puts you in a gym. Then all of the sudden, an angry Brock Lesnar is standing over you. You have 3 choices (made with **Javascript switch cases**). Spoiler alert: None of the choices end well for you. After making a game based on The Rock then Brock Lesnar, I guess I'm ready for Wrestlemania :D

```
var user = prompt("You are working out at the gym when all of the sudden BROCK LESNAR is angrily standing over you. Are you going to TALK, FIGHT, or RUN?").toUpperCase();

switch(user) {
    case 'TALK':
        var persuasion = prompt("Are you a persuasive talker? (YES or NO)").toUpperCase();
        var breath = prompt("Do you have bad breath? (YES or NO)").toUpperCase();
        if (persuasion === 'NO' || breath === 'YES') {
            console.log("I don't like your chances since you're not persuasive and have bad breath...");
        } else {
            console.log("No amount of persuasion or fresh breath will save you from this beating.");
        }
        break;
    case 'FIGHT':
        var skills = prompt("Can you fight? (YES or NO)").toUpperCase();
        var info = prompt("Do you know how to counter the F5? (YES or NO)").toUpperCase();
        if (skills === 'YES' && info === 'YES') {
            console.log("You have a chance to survive. Slim to none, but a chance none-the-less.");
        } else {
            console.log("Just go ahead and say your prayers NOW.");
        } break;
    case 'RUN':
        var speed = prompt("Are you fast? (YES or NO)").toUpperCase();
        var map = prompt("Do you know where the nearest exit is? (YES or NO)").toUpperCase();
        if (skills === 'YES' && info === 'YES') {
            console.log("RUN FOOL!");
        } else {
            console.log("You need speed AND a sense of direction to escape on foot. When Brock catches you, just take the beating like a champ.");
       } break;
    default:
        console.log("Say what? Hit Run and try again, this time picking TALK, FIGHT, or RUN!");
}
```

**Link to tweet:** [MightyJoeW Day 43](https://twitter.com/MightyJoeW/status/842211821721382912)

**Link to Work:** [Brock Lesnar Escape](https://repl.it/GXrA/0)


<h2 align="center">Day 44: Thursday March 16, 2017</h2>

**Today's Progress**:
- Warmed up with some HTML, CSS, and JavaScript (using [JS Fiddle](https://jsfiddle.net/) for the first time)
- Project Euler

**Thoughts:** 
Nothing too much today. Some minor html and css followed by working on the Project Euler project 1. I was able to get 2 of out 3 components of the problem set up correctly on my own (couldn't figure out how to print the sum of a list). 

<img src="https://lh3.googleusercontent.com/h0pwrQLFNCcPq1oAGDyu-Ks3xJLIunHgEHhlMi_1lwK_-ftKxicjVs3wbEQMtAxLFPXcZ1OnLhemwQ50_yr7yxybsKA7uwUalsk6WGsTctbrhqTWdQ851PbzY2R7NR11rJFUy-9-vqLUmqt6vsifpUtysvqt3Kl70CHfBkOphRPwWMW9rjMHLDS-4xxnnWkt3srvH0lZm2tmLF-qmzAglNi_mDHz2vlo-aCL8fk7Vr2e0iIulwlnOUzMTpIrjzZHloRwtQEWOEscQ8xXaYZFXIP9HjpxmgZSSqTpAIlImMy0JgHjr73ISPo6Z06Ko6BoviBpH4h-8mGsmM6i1ERfjjtvHQFXxgpMoZdOxY4M7AvrKls2yr1MhjKsZheO1kakqPAi2tJOZwoYFnAcYXkh6ULW6O9qUMJw-MKz_eu5_s_5G48l8DguPFxHs92GMdDGVhS4_HcO2aL8afAR4Ju9ySnT47wjwA29XQbYgnPtbJlrPusmR_vy5WfdE1cqqLMypCj6nizuPGKnV69qi4qX4ukelQoaILvketB4SVDXxH64027u_qj8bJwhi0Rc5WYH8LFPl7VLn39tiBK53bV8xO-S438-RzAdHYn-EVEKPPxXUIlOZyqWEQ=w1278-h305-no" alt="Project Euler 1">

```
var multiples = function(num){
	var sum = 0;
	for (var i=0; i<num; i++) {
		if (i%3===0 || i%5===0) {
			sum+=i;
		}
	}
	return sum;
};

document.write(multiples(1000));
```

I ended the night with some CodeCombat (which is unfortunately starting to get on my nerves with the bad lag). I read on multiple sites that it works best on IE11 (ugh).

**Link to tweet:** [MightyJoeW Day 44](https://twitter.com/MightyJoeW/status/842514320424652806)


<h2 align="center">Day 45: Friday March 17, 2017</h2>

**Today's Progress**:
- revisited [Project Euler problem 1](https://projecteuler.net/problem=1)
- revisited Web Development Bootcamp array problem set

**Thoughts:** 
Today was one of those days... Poor focus and stuck on array practice problems. Also, I'm about to the point in the Odin project where I got stuck in Free Code Camp and the Web Development Bootcamp. I think I'm going to just slow down and stay here as long as I need to (arrays, objects, etc.) I kept hearing to keep pushing early in my coding journey, but I've got to get a better understanding of this stuff. 

<img src="https://lh3.googleusercontent.com/nETb5ztYtnULU_AAhDSN8Swq47YE1sadIoSVq4L0E8jwImLa1H32ElNF3_n0He8QfzhjjSf8KqilwV9zydo7ZtjW4lPuWBLIBpDAlkdS8Zl1rZhJQ6mYCBJ_dDvGFT4c1fguRvj6tS1rL6Mf0OoWmws7uLdvVLxK-dW0OlGtERktsvcV4s_GoU5It6LtbmScUJmfW6vdj8a5cpG8VdA-aVJhnGz7hCzEvBqcWqQqYK0ONRRsp-M7U3WxERRyTsk82g7uIE-yrIyecXjchFvxZbzCgL1YDOosEbIZyDaRCXpTlLPyZBf3Dq5MjznpqTo7wtvcENdGUpS1jI6Haef1t0adPScsedfDpvztfyKtHVRGevLQEG2OucHguBQCetuf2rI2z8HtKCOiHh5YCURhyB6Rl5wjmfZVDIaJ7IvTFC7kRjsoBV_1vic_78Ptua_6a3EDrLgmCY00OSYLS7TlJ7r5CAuCSh-PNpNpb172MtEs-JnBassRwAgrdlGhVAh_43Z5Rs3UjiQYHyGbzOOCIeVv-lPCq6RenuiG3FtS8zlgvFa-XRXIDf1DbdLtWAH6-nxDCsRRrTbKm91Eujo3yULNQW1xqC1yThx4L-h7VT138LDNQgjauQ=w1146-h627-no" alt="Odin Project Javascript section">

The good news is that I understand what's being asked in the problems, I know what needs to be done, I'm writing parts of the code correctly, and I understand the logic in the solutions. I've worked out, played sports, and played instruments long enough to know that learning something new TAKES TIME so I just need to be patient and persistent. 

**Link to tweet:** [MightyJoeW Day 45](https://twitter.com/MightyJoeW/status/842941097391415296)


<h2 align="center">Day 46: Saturday March 18, 2017</h2>

**Today's Progress**:
- Continued Odin project (completed Code School's Discover DevTools)

**Thoughts:** 
I had no idea how in depth Chrome's Dev Tools goes. It is absolutely loaded with features. This will be something I come back to later and often.

**Link to tweet:** [MightyJoeW Day 46](https://twitter.com/MightyJoeW/status/843322359780139009)

**Sidenote Jones**
I just learned about the ColorZilla Chrome store app. It seems very useful and convenient already.


<h2 align="center">Day 47: Sunday March 19, 2017</h2>

**Today's Progress**:
- Working on Additional resources section of JavaScript Odin (creating Contacts List app with objects)

**Thoughts:** 
No Free Code Camp meetup today :( Steadily moving through Odin Camp (just about finished with the Codecademy JS section of creating a Contact List).

```
var friends = {};

   friends.bill = {
    firstName: "Bill",
    lastName: "Grapes",
    number: 8005882300,
    address: ['Works Way', 'Redman','WA','98052']
   };
   
   friends.steve = {
    firstName: "Steve",
    lastName: "Jobber",
    number: 7732025862,
    address: ['Mac Daddy Lane', 'Silicon Valley', 'CA', '12453']
   };
   
   friends.mark = {
    firstName: "Mark",
    lastName: "Nuttyberg",
    number: 8664752948,
    address: ['I See You Road', 'Fort Worth', 'Tx', '75409']
};
   
  var list = function(obj){
      for(var firstName in friends){
          console.log(firstName);
      }
  };
  
  var search = function(name){
      for(var gimmick in friends){
          if (friends[gimmick].firstName === name){
              console.log(friends[gimmick]);
              return(friends[gimmick]);
          } else {
              
          }
      }
  }

```

**Link to tweet:** [MightyJoeW Day 47](https://twitter.com/MightyJoeW/status/843688120524722181)


<h2 align="center">Day 48: Monday March 20, 2017</h2>

**Today's Progress**:
- Finished JS Contact List exercise. 
- Working on Objects in Codecademy

**Thoughts:** 
I'm understanding how to use Objects more and more each day. In a day or two, I'll revisit the Free Code Camp objects section. I stopped on Manipulating Complex Objects last month before turning to Web Development Bootcamp and Odin project for more help and training.

**Link to tweet:** [MightyJoeW Day 48](https://twitter.com/MightyJoeW/status/844050073755553792)

**Sidenote Jones**
I worked on music for the first time in about 9 months and actually enjoyed it. I’ve had many jobs related to music over the span of 14 years, and I had finally hit a point where all of the enjoyment was gone. 

<h4 align="center">The Last of Us main theme piano (click image for video)</h4>

[![The Last of Us main theme piano (video contest winner)](https://i.ytimg.com/vi/0eacOSCYwnc/maxresdefault.jpg)](https://youtu.be/0eacOSCYwnc)

Being passionate about music for so long and growing to resent it was a very strange and confusing feeling, so it felt really good to have fun creating again without the stress of lack of preparation time, having to regularly learn songs of a genre that I didn’t like at all, and being in environments I was uncomfortable in. 

<h4 align="center">Tetris Blitz remix winner - Mighty Remix! (click image for video)</h4>

[![Tetris Blitz remix winner - Mighty Remix!](https://i.ytimg.com/vi/Fj-jmWTxrMQ/maxresdefault.jpg)](https://youtu.be/g1AC8zxnXcM)

It’s something I’m sure I’ll have in the back of my mind as I continue my coding journey, but I’m NOT going to let that stop me from pursuing this dream. If down the line I end up not enjoying coding for similar reasons, I’ll deal with it then but I never will look at experience and new knowledge and connections as a waste. Plus, I didn't know if I would ever find anything else that I'd be passionate about, so I'm going to keep pushing forward and enjoy every minute of it :D


<h2 align="center">Day 49: Tuesday March 21, 2017</h2>

**Today's Progress**:
- Continued Odin Project (JS Objects in Codecademy)
- Went back and completed Free Code Camp lesson I got stuck on last month

**Thoughts:** 
I can't believe the problem was that I didn't write ONE FREAKIN COMMA!!! I switched my code around so many times on the Manipulating Complex Objects problem. I ended up going through Web Development Bootcamp AND Odin Project because I thought I didn't understand objects correctly.

<img src="https://pbs.twimg.com/media/C7fkiSpXkAEEdsn.jpg" alt="JSON Missing Comma">

I felt like my understanding was there by now, and finally Googled the answer and found that I was missing a comma... My goodness. Well, I am happy to learn that I did understand the concepts but just had a syntax error.

**Link to tweet:** [MightyJoeW Day 49](https://twitter.com/MightyJoeW/status/844396576504254465)


<h2 align="center">Day 50: Wednesday March 22, 2017</h2>

**Today's Progress**:
- Continued Objects work with Free Code Camp and Odin Project.

**Thoughts:** 
Brain and body fried from work, studying, yard work, and working out all week... I am progressing through Objects and left off on Profile Lookup on Free Code Camp. Not sure what to do at the moment. 

<img src="https://lh3.googleusercontent.com/1L6lw26kj_rionXuidkuYkNM-QV4UFUyYJqkCPZai-h71VudJ9d3DbGRgAbVfoYD-4gkmHCvzef2P9QxrkSU6t3VX3NB_jX3sKBngzNBOmSyWj381e1iBuqwSOEMHPxDTzBoo2T0sNhqYH2k1o0iDNEXIh3BfctajFiffWZ8QxOcn6r4jUIRjpdHstuKkse9RyXuWh6SRyCUH76MWAr4gHEY8eW-GABF4gHeIvuSrQ3rVLizpupTmXWKWqV1PjY3xusPsgDnex0DOP2W-hRwEcD0rLbO3AmdKIiyooztVJNz4WSU8St4T1cAGcp3i49t2AQhDSnDxbChxBAnju9TE1LxxACRIZA1rI4heGctAagGP-BWbLWb9mSy1-8pR4O9lcGljf1ohru0gtGr1lfYX998gr-CzqXTUDpaRuFrdDHTxnGlYq0vnj-aHAf15huP8JprGErXlszqGVGk1bWYWnT4UBPMkre8OH9ik6rQyCZ0gr5UHmxgNUZtlo8QilCL5Mcklme3qDfArzmMuG4rTOWTOS7Bthla9YaxHk_0lZuQK2pL1SptGMKvDUijv4UtM_5FO4L4_84tSMFUUjztaGiIDdCEj3EXhZCQf8XYqAq1CqzvVhAolQ=w1278-h564-no" alt="Profile Lookup">

I'm currently Sleepy Jones, so we'll see what the good ol brain can cook up tomorrow.

**Link to tweet:** [MightyJoeW Day 50](https://twitter.com/MightyJoeW/status/844758097948098561)


<h2 align="center">Day 51: Thursday March 23, 2017</h2>

**Today's Progress**:
- Finished Free Code Camp Basic Javascript section.

**Thoughts:** 
I kick off the second half of my #100DaysOfCode challenge and quest to **getScript('Or Die Tryin')** with more Objects work (mostly constructors). Honestly, I'm getting tired of these Objects and lessons. It's about time to start making stuff again, dangit!

I really want to buckle down and spend more time each day coding. People are out here beasting for 8 to 12 hours, so I know I can be doing more. Upward and onward.

**Link to tweet:** [MightyJoeW Day 51](https://twitter.com/MightyJoeW/status/845135847561179136)


<h2 align="center">Day 52: Friday March 24, 2017</h2>

**Today's Progress**:
- started on an About page for one of my sites
- complete Intro to Objects 1 (Odin Project, Codecademy)
- started on Building an Address Book

<img src="https://lh3.googleusercontent.com/NfnLgM4t-EyLrT0YZwugqp6O3Um5qkofYGDKG2eVVnWOFLpNZBv0VO6yJWzUENuqZdw6XHBrLfivXx-gKcWZF1_7a_rk_ZkPaWjaANVrctIrEki3-TesElk40Rcp3Uyxyr5NniQA9lD35_ZQQREx0idRx7bCq2x4ENjndqs3MBqllZa1W8UZood4pqSTgzXvLr2YPBtsHO-EU-TPMoUjN57-GIA1JH_M1bwgCjiDbc9BlpX2Qym_yhMIKdkSolyvEalrj-bOBTFxE2DBze1zp2YDkf7AzvEC3wcCn6kus1YUYevOJoeC-tD-iJNExiH9GNyUXiz2F7oDYHXDTj8JS8ixImv80-OktTz04FUB3t1_yIdxVPyZhg_3wu6ZrUvy0FvsSZ3F2U0OqI1fWQCOU2rfCD9YrDYOsROQePUIxZQWOXz_esVOyUfsquK85iVMJpBFSqUSvBUr_2zcizMCeWc7re88YgAuftHqO-Byd9Pzv_HTjiXeXOkDRQecllPum4z-vcLcL1qn2TUg2kk7wN7ajXrZbj9no2DIiybFRjRzckTpZ7JUIhj2jsfx2PIjlzJ8PL7oVIRoAGeO__oKwocz63jHCqEMPLUyiu9206TDDDbRSWTcPA=w1278-h621-no" alt="Games and Keys About Page">

**Thoughts:** 
I've seen more Objects than I ever planned on seeing this week, but the repetition is definitely helping. I also got away from lessons for a bit today to work on some html and css again with a bootstrap About page. 

**Link to tweet:** [MightyJoeW Day 52](https://twitter.com/MightyJoeW/status/845512972055318528)


<h2 align="center">Day 53: Saturday March 25, 2017</h2>

**Today's Progress**:
- finshed Building an Address Book (Odin Project, Codecademy)
- continued working on Free Code Camp and Odin

**Thoughts:** 
I can tell that Objects will take awhile to fully grasp, but I'm feeling more comfortable with them each day. The this.concept is starting to make more sense.

On another note, I think I'm going to take another crack at [Javascript 30](https://javascript30.com/). I really want to make my own unique the Javascript drumkit (or full music experience). I should have a much better understanding of what's going on than when I attempted it a couple of months ago.

<img src="https://lh3.googleusercontent.com/uicyjcWoM8G642Bxi_Baf9lpoxQfWOpk78qJms02s_0si3IUMO0UsNQgQcR56zDVTOHEKklqJsqJ2tH4TGy9uzo49YkV6dtpK0FstTLi-W_6JG9aLvAzM7QNqv7r_VpANWf7q66MmXhz-kVbOi3E_WXfhRCgaiOrejTyp36gfRxSQ2PXKrGWDXJ7l-lUrNh-CYZSd01CtSVpieK9FGyE0gFA8MvSuIwbJFnWiutHdvD0DPk1A5wdwBIMvO3ye3dgx_aEkYqFgj5ACstUqSlboE1tEVa5KQfCbbrXRC9Q2oeEp3Tt-HQB-PmuNT1JzGsAg2vGyb47Om1As9r496WllX5_yYFaDX-hjzvKqOZXukCqgSlpPSA8-KAKzCnOUfSrmS1J5tHbrCz8hF8BUHl0Sow7Uk5ChTLqTMszgmnJBfNzKKRqvLAC57nYsDAqzgEhhBdyw-dpq2jl-4jx3GuYA3Wluxo23TsaPpSPJGM0H197hsPECyPMQ9zEtO48yjGBZv7qsc-QV4UmHO158Xbl0l393s4ebQGSbMKo77eyQSZbRqsUAM0XXW_MRcX9CH51RoANJ2Lri5cqlRqUjxy_NzrtUH5vVkSsR0Vogd31EF26afNJB2a1-Q=w1280-h702-no" alt="Javascript 30">

**Link to tweet:** [MightyJoeW Day 53](https://twitter.com/MightyJoeW/status/845864129973927937)


<h2 align="center">Day 54: Sunday March 26, 2017</h2>

**Today's Progress**:
- Free Code Camp Meetup
- Finished Object Oriented Functional Programming section in Free Code Camp

**Thoughts:** 
Today’s Free Code Camp meetup began covering Angular 4. I’m not there yet, so I went with the group focusing on HTML, CSS, and Javascript. Time flew, so we didn’t get to any JS today, but we’ll continue next week. 

At home, I continued going through both Odin Project and Free Code Camp. The .reverse section helped me solve a problem from The Web Development Bootcamp. Although it’s taking me longer, I love having multiple resources. They are all helping me with each other. 

**Link to tweet:** [MightyJoeW Day 54](https://twitter.com/MightyJoeW/status/846205910255063041)


<h2 align="center">Day 55: Monday March 27, 2017</h2>

**Today's Progress**:
- Finished Javascript Basics section of Odin Project (Codecademy)

**Thoughts:** 
That Codecademy JavaScript track was loaded with new information to me (definitely not basic to this man)! I learned a lot, I will forget a lot, and I look forward to keeping this train moving :bullettrain_side: 

**Link to tweet:** [MightyJoeW Day 55](https://twitter.com/MightyJoeW/status/846568705484095492)


<h2 align="center">Day 56: Tuesday March 28, 2017</h2>

**Today's Progress**:
- Completed Codecademy's jQuery Track sections 1-3
- Halfway through Code School's Try jQuery

**Thoughts:** 
I hadn’t used jQuery since near the beginning of Free Code Camp, and I forgot how enjoyable it is to use. I plan to be finished with the Odin Project jQuery section by tomorrow.

I have so many things I want to do, I don’t know what I’ll do after. I want to get back to Web Development Bootcamp because I felt that I was learning the best with it, but I want to continue working through FCC and Odin. But then the creative side in me (which is the majority of me) wants to focus on some other things.

I want to revisit Javascript 30 to at least create the drum kit. I also want to get back to spending time with Arduino. The good news is that there is no shortage of lessons and projects, and I’m not in a rush. I do want to learn everything and get working on real projects as soon as possible, but fortunately I’m in a situation where I don’t have to rush the process.


**Link to tweet:** [MightyJoeW Day 56](https://twitter.com/MightyJoeW/status/846940508454825985)

**Sidenote Jones** 
jQuery sounds like a rapper that's about the drop the hottest mixtape of the summer. He would rap of coarse about `$('.straightCashHomey')`


<h2 align="center">Day 57: Wednesday March 29, 2017</h2>

**Today's Progress**:
- More jQuery lessons and practice

**Thoughts:** 
I’m enjoying learning about jQuery again. Everything has been pretty logical so far, and I see how this can save time and work. I am getting into some more difficult processes, so I need to keep focused and work hard.

On another note, I can’t get the thought of jQuery being a rapper out of my head lol. Anytime I see the name jQuery, I’m expecting to see a release date for a mixtape. 

<img src="https://lh3.googleusercontent.com/AIbfIwx_QxTO1-83GahD4ARqQHDLFH58cwhBINvhe6pGcQpUKRM09QANHL8GsnZeGBcc3madyxDvUCXKiMpUxRU7YPAayRF2dxggRRorSvorWcev_8qDCedt8xpswJ9zuy2Sr_ntD3CWZhk13tjskuros1vCcaMqYgxLjKAq2RXfIC8VXCRTQx4S_KXoslidLPTetV3To3BGVbq767_aFz4RDz-5xzIQAcSTaMbPzKpcjQy8U4hGHsg19SPPPGBabFuqmbF41IjYauvgqN-xqFYQS70syU9XMGv0XCpMHT6Yowe6tj1ybPgSBS5wE-A0Rbh14G7IbUCzK8oOScHbazy3MEP1ChgnPdSgidghHOLQQ2hVjHxRvVStGFOqQOP-gwah6zFuQ3WLEA9IFdqJCJfLnrfpd8p_fKYzd6jqG44mfGn8GJhhvTmMRiq_RCF623uJlCiVpNRaJjveamLoIq6OiOZqvKkv25dMxSY-7m5qeT4JFrauY5XdVvbfuHz9yiGfFF0MmljWLsNs6tQLxLo4s6Ml3kWVqyA6AKvHmlOhzMyePZXUjbpyLy85q6b9-vuil0HORBvk10uNqFyWx4aZjUgxm6owJxK8HKktjZu-Nuap3ShktQ=w628-h364-no" alt="MightyJoeW jQuery tweet">

**Link to tweet:** [MightyJoeW Day 57](https://twitter.com/MightyJoeW/status/847311787108163585)


<h2 align="center">Day 58: Thursday March 30, 2017</h2> 

**Today's Progress**:
- Continued Code School's Try jQuery course

**Thoughts:** 
jQuery started to become Confusing Jones during the Traversing and Filtering section of Code School. Things are starting to sink in more though as I was able to apply some new concepts to some of my old code.

**Link to tweet:** [MightyJoeW Day 58](https://twitter.com/MightyJoeW/status/847684792019673089)

**Sidenote Jones**
Russell Westbrook MUST win mvp! I love Harden, but Westbrook is averaging a TRIPLE DOUBLE! And not regular triple doubles. Monstrous 50-point triple doubles WITH wins! I never thought I’d see a player average a triple double.

> Here's a quick mvp switch statment I put together in [repl.it](https://repl.it/).

<img src="https://lh3.googleusercontent.com/H826Fr1n1vtgge6giqomowPTrofQt2WFW3tknJ3FrWAJGeSLZdWqAEImPZ3MDJpQ5gb469nMj85CeCqM3c23yVkOJ0Oy9KSmORS9Wk2B8vNLgfL_M_8uppa449755Wh-FgIwmRVGOaNMPlk0a1AcPPDDeOuaTJrYpwGwZvhgIdl_0Ko5PXbnsqNamAqriOXJtCxl8GsUaTPK8zdWBiqXtfjlY5ML0HmZmr77S-3_kpHDpUp_sS5MluqdY0Dpc4_I3qGPjRRiTDIXb8HsT_z5YTMFxhOpm8Hw34uOIK6OUf74tdzNUYjsAbIvXChUQgvOUlVAXEOkDCB3S4NDUZhLhZS7dBP_mWuou8tl4p_imAldPePNoKYi9ASFSX9FvriFTuCOHywrVtYsNBxqKQz8eWk0gCND0waS2d-1s7gHsJpe1GjOL0hZCDLojan6kLor7IftVg-NlH1Hj9hhnLvCLPn4QH46t6yWuzLXDKgJap9LjKszjujirJ6LihBjy2CcqtA2JH7wEo7M5l76jlwdvB9m2Tx2RrST1GujOl6uZjAAIIWEVHfB74iQ33hHLbohcrDs9YYc0RVUCEN-6M_jYuSSGr3-CCLnNx-FynNcv8_eWScuZOz4Ow=w1278-h607-no" alt="Javascript Real MVP switch statement">


<h2 align="center">Day 59: Friday March 31, 2017</h2>

**Today's Progress**:
- Returned to where my code journey began with Intro to CS from [Google’s Technical Development Guide](https://www.google.com/about/careers/students/guide-to-technical-development.html). 

<img src="https://lh3.googleusercontent.com/WlJZNxU5Qs1WhOGDBS6nbxMlgrmvz6a-HCTcdFOB5E-H5GZWLXDqirOmTghCwHjegkGvdvXKkQU1hHZybaGr-96lkZKu912cxXgYnm9o72CPCIFqS_T9m1d8n9uc3kUjzKkGdarGH1ZrO78siXZGrkathrElspzAd5xKcx6KpiqucPEMSYjORHVIyxUrBpTx7R5ACAcy5co4w3qGCNqwOVN7GMdrBLj8EEqilrqcbtPHnFCFn2rKgu2OaTxm9n7SO1d3c7V__5SX59imAkuTDu2Lyni81F_-z2s-tga3J-TdPYC0EfEFfXErd7Ml_63Gz2uwPwXjGW2s8So2o2zV3Hvs8UIp-ODzElkH1MMLz-XFOpunL8D7PjYlYgZDK3Mvqw59LUxoeDBUWNe4G2F1GT39kKU29isLznt2EtDRgs5Sqj4UuQTZkFLKoGKWKPkg5p6-emsmHe_nHqeIrRwE6BgAqssns-Wafhd98Jd1-vCY06-Rl49kD38Eg5e3spcdp3Zrr4vWoWgU9K22Zow0K3Au-NwzHYr5VR17Z84sX-OIHKQRGvkrcygdKFLOEaiKzIK1_cvSTMRSVCglSWj2rLfdRLwCJh3NkbnnyMfBSxQO_uGgB-uIkA=w1244-h545-no" alt="Google’s Technical Development Guide">

**Thoughts:** 
After doing so many different courses and lessons which mostly focus on front end web development, I wanted to go back through my original goals and plans to make sure I was still on track. I originally started following [Google’s Technical Development Guide](https://www.google.com/about/careers/students/guide-to-technical-development.html). There are many things I want to learn how to do beyond web dev, but I’ve been deep in this world with Free Code Camp, Odin Project, etc. 

I still have the freedom to experiment and the benefit of time, but I do want to make sure I’m focused going forward. I’ll plan to finish the Intro to CS course (which focuses on Python) while progressing through Free Code Camp. I think I can move on from Odin at least for now (great material, but I’m wondering if a lot of this is becoming dated i.e. jQuery, Ruby, etc).

**Link to tweet:** [MightyJoeW Day 59](https://twitter.com/MightyJoeW/status/848041600693542913)


<h2 align="center">Day 60: Saturday April 1, 2017</h2>

**Today's Progress**:
- Continued into Unit 2 of [Udacity's Intro to Computer Science](https://www.udacity.com/course/cs101)

**Thoughts:** 
It’s interesting to see how much of programming is similar across languages. I’ve been spending a lot of time in Javascript these last couple of months, but many of the concepts so far are similar. When procedures were introduced, I thought they looked similar to functions (turns out, they are very similar). 

<img src="https://lh3.googleusercontent.com/lX9SCDNW6S8AHzuvPAH0fHXYi_9nSZ2UqQsroLUVC2jD96kHBlKXdNzDY3fFFCDRr-zx_fWp5kqrRo3ZoeZxc98JicuqjK9D558DRtjLXgUz6eIty4ccwbMqAjUUDngJEynPC0iGqHgnM6-KkIwXykeiwhn5BMUQe5Rn-dqSoveg5JFs4QzQi8IG0ws44BGoDGhESwmIMWXHgF6OBvkZ41pup0wfrCkUzbQKwNicoK_DA_K0oDPgng2uML59spM5jfU_vt_gRWEKQ_TQJe51McpaK_j1xAAzHYwDhX5CZLZLLmU8MRm2xbk3C7r0bUVTzJew9ZpUUThDiyJqxaM8z_72NqexdJ5bAB1VPhaveb1wgwu3cNTvzc_9tlCDCG9RgojzSQLgKEBt6P4LYTqIab3LBv9yqtFfhdM6jOOgU9MojmgLmxw1ND-qdriN9d34rcrU3ZUwmBSwHcEOcYdcWY1Iv6RfngawZjVc_bMggkgWTYIhCph15udcBwJ4L36Hz3PWkS2B6nehwYbE7Sk9UEcPgYXVf-3Q5Nd8CsxsBnoE5EZtHNbjpFj8tn5lZXoG8dCabMFslli1ijrhaQFL4ESRpkWBI-zcPiS5jf3_lrgfcEtanjQMIw=w1265-h617-no" alt="Udacity Intro to CS">

However, Unit 1 had many things I hadn’t done before such as web crawling and extracting links. This stuff is tough at the moment, but having html, css, and js experience helped with that as well.

**Link to tweet:** [MightyJoeW Day 60](https://twitter.com/MightyJoeW/status/848041600693542913)


<h2 align="center">Day 61: Sunday April 2, 2017</h2>

**Today's Progress**:
- Solo Learn Python lessons to supplement Intro to CS.
- Started on Weather App at Free Code Camp meetup.

**Thoughts:** 
I can see why building this weather app has caused so much heartache throughout the community. Luckily, we are working on this together at our meetups. I'm not to this section yet, so a lot of this is over my head at the moment.

> There is a lot in our code, including this Kelvin converter

```
function kelvinToF(degreesKelvin){
 return (9/5) * degreesKelvin - 459.67;
}

function kelvinToC(degreesKelvin){
 return degreesKelvin - 273.15;
}
```

**Link to tweet:** [MightyJoeW Day 61](https://twitter.com/MightyJoeW/status/848671868940931073)


<h2 align="center">Day 62: Monday April 3, 2017</h2>

**Today's Progress**:
- Continued Solo Learn Python lessons to supplement Intro to CS.
- Worked on a Python calculator

**Link to tweet:** [MightyJoeW Day 62](https://twitter.com/MightyJoeW/status/849134193359630336)


<h2 align="center">Day 63: Tuesday April 4, 2017</h2>

**Today's Progress**:
- Completed Solo Learn's Python 'Functions & Modules' and 'Exceptions and Files' sections

<img src="https://lh3.googleusercontent.com/8nxbsG3-VKiBxm8bPvRgoOyhD5a7gV6bmUXGeq7VndkXGlM2UYvE3GFvj7A5LRTAj_gfcqI7-Oor6Mw7f8VPlbdd9hUQ18-tg4TSZl1F9y6X-1Fc95NcAfYLcOYryRpNPa7w6jyD6BoMG_pcnhNC6BjN5Kf2lMKdVHQXnco6T1lkVzT4Fm-kVkokDX135AZkemnMKdE_SMGrLm7N1s6fiIileLuC15sCVn2M9EZFdwQ0-vmHMW85xGBpaerGr1Hpruaq_BBN-KYR3CPr2M6wHR-P8puzK657hxkwmHVSzKM-suC_qv90NLE0vzuXtqkrfg4jYsm8hRR8P3wTXwaZAFUjaODYn6_PSjpZESrF1U68gGMkHDz8mwJ7wEB8i-hIGh_dTXSCz1BjOD7g9WV7rUNCL6sNPOKbGAyX1lGmf76-op6tRVf4GrtHJDnfSV4hlh40EbYiU8_3m7YDzSdJRn1hiDE4pqkkZsugYfk2zZp-K7fHaH6tvofbKFHZBTPLiqliASjY8dZ2ABQ6IMQ7-RxHo7V-8tC61v5uRJvLj8sQyte5JWGIc9CDOwST9an-o29g6-DXNf2tPf7Z_kokSaXuikoYGEjTePib0vuj5l6YbmOw31pb8w=w1247-h622-no" alt="SoloLearn Python progress">

**Link to tweet:** [MightyJoeW Day 63](https://twitter.com/MightyJoeW/status/849472826960642049)


<h2 align="center">Day 64: Wednesday April 5, 2017</h2>

**Today's Progress**:
- Completed Solo Learn's Python 'More Types' section

<img src="https://lh3.googleusercontent.com/5rS5sW2ZC7_kpah7JL18-mBAgVvodX0rh589ZQh5seWI8pIsUpINggSEJy5HUWDmjtRgPFb2mnPHYpe0DeEdaX40kQKUMdEoeZOAN88JdkndhCys8pcK1JgIW5db1G6hpybI6HATVJ8mrRmkuJbyeaeD7fraLPjBJ-sudAyxD_PzOEOzN2qXPrhsvHdI8Ym6IiUPdTCbkPoW1NZrBBy-7yUJveeGDcapKvpfeWBjtsYEUlbxjHLtQAn0l03kF5FCQfJ-4Xg6zznY1l2II23We9wJc1oOVpaxwUyIGqv29S9M2PrXpLijiQMunC047SDj2ewZZhGetoUjFW0u3ERL3TPaPLnPUOSD7Smfz66YpPmPXzLbRZwL3dOuQ2WtZWupsWNKQ5iatXZ1lqFlYfk5fjqbH-s9egRfzIOkjDh5WRYfvg45Jx_jsWrjHCjmvYplTgG_9hBLsj-GuEFhw0A8WZOc4lhtxeog4EDz0uHcCps0Yw4psi5cRWXoqLt_Xvk1H6yOF2GXky14W5fI5s-Oi1YY3cqM9Rdl87w91Av9FLRodAXnFv6ThYZjL-STS_vEYCXfYS548EM6IIfp9d47XGLh4-sNkEP1XfKrYq3zlldv9wNSaoKQTQ=w1154-h627-no" alt="More Types">

**Link to tweet:** [MightyJoeW Day 64](https://twitter.com/MightyJoeW/status/849824770665435136)


<h2 align="center">Day 65: Thursday April 6, 2017</h2>

**Today's Progress**:
- Continued progressing through Udacity’s Intro to CS course (unit 2)

**Thoughts**
Someone has been slacking on the ‘thoughts’ section… Seeing as how I usually code up until falling asleep, I’ve been getting that tweet out and then crashing without updating my thoughts. I’m stopping a little bit earlier today, so allow me to update you, friend.

I’m still working through Udacity's Intro to CS and Free Code Camp. It’s interesting how your perception of something can depend on what you learn first. I can look at Python and Javascript and objectively say that Python looks and feels so much cleaner, but I’m still used to the convoluted syntax of Javascript. I’m used to seeing curly braces, parentheses, and semicolons all over the place.

<img src="https://pbs.twimg.com/media/CCdC1HMVEAElN-e.jpg" alt="Hide and Seek Champion">

I’m glad to see that I continue to figure out things that I wouldn’t have had a clue about not too long ago, but I feel that I need to step it up. I’m already on day 65. These days are flying by, and I need to set a goal for day 100. I haven’t been creating content lately (it’s been all lessons the last few weeks), so I do want to set a goal of having something created by day 100. 

I also need to devote more time daily to coding. I’ve heard of people that spent 8-12 hours coding when they began and there have been too many days where I barely got above 1 hour. No excuses. Make the time and focus!

**Link to tweet:** [MightyJoeW Day 65](https://twitter.com/MightyJoeW/status/850167336455864320)


<h2 align="center">Day 66: Friday April 7, 2017</h2>

**Today's Progress**:
- Continued progressing through Udacity’s Intro to CS course (unit 2)
- Practiced with button onclick in HTML, CSS, and Javascript

**Link to tweet:** [MightyJoeW Day 66](https://twitter.com/MightyJoeW/status/850537127045726208)


<h2 align="center">Day 67: Saturday April 8, 2017</h2>

**Today's Progress**
- Completed Udacity's Intro to CS Unit 2
- Completed a Free Code Camp Basic Algorithm Scripting challenge (Factorialize a Number Complete)

**Link to tweet:** [MightyJoeW Day 67](https://twitter.com/MightyJoeW/status/850906962178998273)

**Thoughts**
Alright, now I'm not sure if learning two languages at once is more helpful or harmful (in regards to spreading confusion). I really wanted to complete Intro to CS (Python) first based on Google's Technical Development Guide, but I got into Free Code Camp not long after beginning my coding journey which focuses heavily on Javascript. Also, I am wanting to get back into Arduino to start working on physical projects (Arduino uses C++).

<img src="https://upload.wikimedia.org/wikipedia/commons/3/38/Arduino_Uno_-_R3.jpg" alt="Arduino">

I want to stick to my plans, but I don't want to spread myself too thin to where I'm not retaining enough of anything. At the moment, I think I'm leaning towards focusing back primarily on Javascript and doing Arduino in my free time.

**Link to tweet:** [MightyJoeW Day 67](https://twitter.com/MightyJoeW/status/850537127045726208)


<h2 align="center">Day 68: Sunday April 9, 2017</h2>

**Today's Progress**
- Worked on Weather App in groups at Free Code Camp meetup

**Thoughts**
Today’s FCC meetup was a follow up to last week. We continued working on the Weather App together (which I am very grateful for not having to attack it alone). Everything is coming along nicely, and I spent time at home working on the CSS side of it. 

**Link to tweet:** [MightyJoeW Day 68](https://twitter.com/MightyJoeW/status/851264058682523650)


<h2 align="center">Day 69: Monday April 10, 2017</h2>

**Today's Progress** 
- Arduino lessons including Analog Read Signal and Multiple Blinking LED exercises.

**Thoughts**
All of these Arduino lessons and projects go by so much quicker having programming experience opposed to going in cold turkey last year. I've got my lights blinking and nothing's on fire yet so I'm off to a good start!

<img src="https://media.giphy.com/media/3o7bujx4ngGQWKcy0U/giphy.gif">

**Link to tweet:** [MightyJoeW Day 69](https://twitter.com/MightyJoeW/status/851655636412706816)


<h2 align="center">Day 70: Tuesday April 11, 2017</h2>

**Today's Progress**
- Completed Programming Electronics Arduino Crash Course Module 3 - Basics and Module 4	- Control - Unit 1
- Modified code and connected a Joystick to my Arduino to display data for x-axis, y-axis, and switch button

<img src="https://pbs.twimg.com/media/C9Kd-dEUQAAGvJj.jpg" alt="Arduino joystick">

**Link to tweet:** [MightyJoeW Day 70](https://twitter.com/MightyJoeW/status/851921228990492672)


<h2 align="center">Day 71: Wednesday April 12, 2017</h2>
**Today's Progress**
- Arduino practice with push buttons
- Free Code Camp Basic Algorithm Scripting continued.

**Thoughts** 
I finished the free section of Programming Electronics Arduino Crash Course, so I’ll be in search of what’s next. 

With Javascript, I’m still on the Free Code Camp Basic Algorithm Scripting section. I just “completed” the [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string) problem. 

<img src="https://lh3.googleusercontent.com/StATI9xtKxtFAhwDpAl5Qsz05qE-Juduk72o9xjLJgEDDdXNLnFZsCxMcTXh7lgOplGmjYIjCnByzcfSFCj-vbTAZkVsSErlzap2p6B-_o-A890VA5Cy3AAqklSCkZ87sJGSDpZfSb_VE-a9Onk2F6KaUurMncnfPuiFjWaJisPix7iDQCKbSzUCjAnxSV7ymIkKPtHzUnc1ekmL248Iyh2GwhUpEah7-JViNNbtc54BRvfv4xQOSeEtpD6BQNG3D_VmQxiLRLTRyqjeJJN92hElO4qMco1Rj0-Y5xdmiNUCUkIs-lKlunsBQ5t71hUBC6K6Dvqh4jvX3-97B6gUZFTcqaigJ4ESzSaP4SsDW1j5shGJVd_jUKRPNAcybTJmU8OQBMecScY3kwk0fk7AfutOI_qwiYIev3TKhU2Q_nv24AG-q1-adODfUYWGLBUhUrA3LP6_TCY_gWAoGYAgbwayYhzmRvBUjUFl_RU0nLZC9DteusWImJHWszF0uEptPss9X6e3OdFSg2XQvJky_DXzc2X-7BwxfSk4WTJcettxzW2-Im38pai8WNyB_mDopun7AzcdkZpTVKkdEPm_-wmEfcQMKEmIAGw17A6-jljpNrAxIFVxLg=w1252-h426-no" alt="Find the Longest Word in a String">

These exercises have been like a punch in the gut. I feel like I’m at a point where the explanations make sense and I know what’s going on, but I’m not getting to the solutions all on my own. It’s frustrated, but I’m optimistic that I’ll eventually be able to put these solutions together myself.


**Link to tweet:** [MightyJoeW Day 71](https://twitter.com/MightyJoeW/status/852376630588837889)


<h2 align="center">Day 72: Thursday April 13, 2017</h2>

**Today's Progress**
- Experimented with Arduino 1602 LCD examples
- Attempted to follow along with a ReactJS tutorial

**Thoughts** 
I wasn’t able to get my 1602 LED display to display any words, so I will be revisiting this until I get it figured out. I’m not sure if the code is wrong or if something is hooked up incorrectly (I’m pretty sure the wiring is correct). 

<img src="https://pbs.twimg.com/media/C9V7MxNVYAEiX1k.jpg" alt="Arduino LED Display">

On the Javascript side, I ended up on a ReactJS video. About ten minutes in, I made the executive decision to close the video, close my computer, and go cry in a corner… Haha no, but I did do one of those three things…

Back to Javascript. 

**Link to tweet:** [MightyJoeW Day 72](https://twitter.com/MightyJoeW/status/852723357409783808)


<h2 align="center">Day 73: Friday April 14, 2017</h2>

**Today's Progress**
- More Arduino lessons and experimentation

<img src="https://lh3.googleusercontent.com/91ljHxgWlTnykFIBgnt5UthPTGdLGXYUjdqr0q-PuUsfbmpF-OcD19DPrhcTuOwS8LdjOUzdxsDhGSJB2cArYWBs6vUMLooNUFbEvcRrXSXk-jfJtkqcjRaXhYAgmN31E0KfwFonSVdC4ldToIVQtK7lK_Pe0yXf_bUBhbwzLWhdaDAtldMd3ObmJquQbIMCwrE4loVHGfggBPAS0UQ3z0iyW-KBZ1HnG22Ch-bMNs6o5XEw28odbUVaILy2gNYekAbUlEc_KjAfGaGlPqzlIyCRK1NpQhpgAZ2w0CKeM2jnAQR583gebr-GivokTy6Q6rBTQT1SsT6qsglbvs7sGIS4-KsuaDzPoBtJSecFDcJ_Q8QJscMnB6WGeU03qRKnR58M3bTK8vM6_S92w9tFxfJw6qSBRhQeIaQlL6ZBDRuBLBUeYPG9GRWOAyQxZ3pUq5tLo6QB_MHiNTxLWhxzf4KNqCOeFAFY8tw1ZhqY_qkySanWikMK3IXWTHKvc7jgC7etcchJ1YBSLSQJNJNe-L2AUIMXotLpcKY_sBUZA2heRGzUZBQIOpe73eCYM4YalGZMlejVfUaR8Jzg8GsPhLZQE83rkrmJleTuXTCtuoUi_LL1n10tMw=w1147-h627-no" alt="Arduino Code">

**Link to tweet:** [MightyJoeW Day 73](https://twitter.com/MightyJoeW/status/853022422697750528)


<h2 align="center">Day 74: Saturday April 15, 2017</h2>

**Today's Progress**
- Arduino lessons and practice with sensors (out of town)

<img src="https://lh3.googleusercontent.com/Gs6LNznnJKQ8nJOrH_tHVHAYec4eEzoTVSVMprFCumYAZANimXNHx2ZLLfpPgwkPzJZoaJESsgv3tKKxbVs3XuLF_RcSD6NS-AMQPI1XKpCjW6LdxIswW5zy6GV6QYM62NA0o_gIxYhJtdWUzyeBZBml9k8V9vjzESa20qXIsimCQyqWERpbe6aTtmUEV6m5I2oL3U8VukI3Y9MItdYHjyFYf4p8hvv5wDWW_9rFVk7ZvkqF02YAoCArbYtkfz3i_K8zjDIjVdMUHTXrrsnQbOvpgIgtY_Jcp33EA-9NBuSYzBPJEfb2BQxxcMknUjHLfDzV9eBD_O8HqVfYyO0XA1SAOyIjn2w_LRpwfiqgXd9N0JfoH0I_8YEKkB1eQ6H6BCJsarKfHfGhIYCxMDFjNKrOTuG2h-d41qM3K3lcNdKixI_6pxTsP1q83lDc--NPylt5ZOtoUmdwo4lKy1H2lJCW_-iu0iZCX_LTq44BUXRlbxMQ6BKBDXtxDn_cEDkJhR_WnpLiUGZVD4FnziEtFT0ClUjfZtaVyUZ-faDy3AvcIQmMcauIUZUKvEL8_b-5gO4xY9DDQMlG8gbeksN-FEkNG_5fgjn8gMEHtZuvvpR-_CWBvFkmIQ=w1115-h627-no" alt="Arduino Sensors">

**Link to tweet:** [MightyJoeW Day 74](https://twitter.com/MightyJoeW/status/853469101758480385)


<h2 align="center">Day 75: Tuesday April 18, 2017</h2>

**Today's Progress**
- Completed Free Code Camp's Title Case a Sentence and Return Largest Numbers in Arrays challenges

**Thoughts**
I thoroughly enjoyed my Easter weekend. I got a chance to see a lot of family, and we had a blast. Unfortunately for my 100 days of code journey, I missed a day for the first time in 74 days (I actually missed two days). It's alright though as I'm back home and into my regular routine. 

<img src="https://lh3.googleusercontent.com/wwlgeplAeguU8qpjUr0Xm9TtW7LCYtoVvicuTbb7lVZY6XLqVLVizhNVlFGmEiq_SBJzSJtUtIqgeHzcyx29bie-d9nA9zOxYbsyF7X6W16e4_D3oihXmA_6DiglrnUNPK73aeiEJZBmbZdFGloT_5VVlo0LonrdX6bGFDZH8q5qhGBAPjhJQE7xdoE7Nkq5xV0SoebXhi1PSXJhkdpPWsQn9w0ShH_Ok9mdM0400T4sdevGiiUirT4sNF5ZVqDp_h8xDJYF_5gr_Wnzw8Hz11LqaRVf4LzoXRr8ZPeE5hjN6hVF20Xn6kP369-dSX5Q78ExAzLXgwzmz6umPhv1C5Y9PkyhXYGDkJQ9u5atOF6fNZxp7LgKTLVJWSnRR6-kaNki7q8p8uleFsuRu1VzRu5BGyu6A4Zi-yGjGz1Tr1r9SjZfkFS2zR4noqk4x-LzNFZUNxBXBP14q54iiZmowfxXaOpe36aNh-FPQOD92MQEN5FsaywyL2n1tvJGDAIVoOR7liqq0nReyVubNOxfoZQ0pB7uS0rdkVjLMl5dYpPFlRjasZtET6RUHxUZ9Wa75hCunYRan9dAck8Zdh3_hYq4FT_ywKmA4xcABAyea0Wz7GAL3YGHXg=w513-h300-no" alt="Arduino Macbook">

I picked back up with Free Code Camp's challenges (which have been very challenging to me). Baby steps I suppose. Also, I've spent a lot of time with Arduino which has been a lot of fun. 

As usual, I am Sleepy Jones. Until next time!

**Link to tweet:** [MightyJoeW Day 75](https://twitter.com/MightyJoeW/status/854577020826767361)


<h2 align="center">Days 76 and 77: Wednesday April 19, 2017, Thursday April 20, 2017</h2>

**Today's Progress**
- worked on CSS for weather app, reviewed Javascript on SoloLearn, continued Intro to CS on Udacity

<img src="https://lh3.googleusercontent.com/SSr86bkQmfwcDnR5Dh5vLlgFOFr1skH15Ky-fNNVpP_f1oD6e2kvZYQj020TD1Kh_UEILxy08MIhqETvxq7eS9WZFNNweialVbUcd_tJozxehEq1BO4Kdf04uxcqtJOQgthC-Jk3wsiYTM0MQv2HBDn9Oyfyn0tv-IVZ_egeOXh1URyr0FwXE05ybVtwGC4XBeSPvh92HrHJQgnhSNTxZ118k5JOorPlNN6wruZfhDEbBL90Opj-v_2va9h2GdsR6BPpNVob3_hFh3BP61LL8vDAPMOQVFx6jMeIYtXACsMUuWaGZ2QIRQ4aVRxBUlD-umJ-jbbk_IoPVM2KADKsMsP0JzhPoXTnFD-VSEdNf7toZW53uV_bIrRm2EkUqTquPHYgRCK-EdnpkXNo4Uu638W9iLCKL-I_CNMx393H23qLcopD0iSGsOZcm-NQkaz-0BrIqdO9oUuUY4a5MaonTaZQNLuRVonlBeWmiB1XOPyG6mRCFoX2Xa_-H27KnRr8MwRfRZckOi6jK-xU1D8kto4LYr0oCTn6G4K1Hq-kFj8_XWh1qCw0DP_jzkBQmyJIqB_vJFSeiAVVtcLfpk0RsuVtmimitd7DA5HM7lfClKyOuKvPzzczbA=w1268-h349-no" alt="Weather App CSS">

**Link to tweet:** [MightyJoeW Days 76 and 77](https://twitter.com/MightyJoeW/status/855255282703884288)


<h2 align="center">Days 78: Friday April 21, 2017</h2>

**Today's Progress**
- Got introduced to Java then reviewed interview prep materials

<img src="https://lh3.googleusercontent.com/QnEKDsgIg3R23r6RIzDqP4Zq0PYntfrdUGz8HL_6pEZ1YRCzP-JLwdmFFKhIHeBpNYuuyOsn0gbVq2IpR8T_0hO9OnUSBhz6dW_dfxJbH-0R6jFX-G9dhj1CzkYL1i8HXV281Ak2tK7blObLPRg9WbrQuzVkHugyPeGN__K6sX8PX_BStv3D-H2E76aO2bXbXge1K1oahGtO1_U9d3uMu_SSXdT0OnfQh24qiT6cqhkw2O-fnUIfqU9o5Y8wcBfi2kCxjycTGBGNUpjSJ-dVEdnDQ4snWW5Mx_MYB2fwpfapbDpyC3RHUqIyPLtR1SJBax69iNpkvU2YvVa-p_P5JiuBLGKAXg7EVdZ9TF5Lu_POzBMMfVLoOhCZ29aQn_o57WbzWLXOpv8RzEHbi0c6whoESro9s2iAL3yasGy0mmzUcUkj8HtnR9_mkhI2B3hwrtiYlKD-Oz9OCJnN90LquOZD6o0UhFtMLuiM95pCnyWvwtNmHijcOZe0psr26wHWwHDVYet0qbMy1dUUvOqFz5-5zRxyrrPgEaAJHxJyR4eOdhDTD1uE_lMmIi0x7FkqpP2W1X8Kso-7eBbHVsvqYAPW7OYAzhGgo8n-JTx-ndOCleL_VIjlEw=w1278-h619-no" alt="SoloLearn Javascript course">

**Link to tweet:** [MightyJoeW Day 78](https://twitter.com/MightyJoeW/status/855638606463074304)


<h2 align="center">Day 79: Saturday April 22, 2017</h2>

**Today's Progress**
- Worked on Python problems
- Practice white board coding

<img src="https://pbs.twimg.com/media/C-E6ADbVwAAscgG.jpg:large" alt="White Board Python code">

**Link to tweet:** [MightyJoeW Day 79](https://twitter.com/MightyJoeW/status/856029387275325440)


<h2 align="center">Day 80: Sunday April 23, 2017</h2>

**Today's Progress**
- Added fahrenheit/celsius toggle button on weather app
- started Free Code Camp beta
- Created a local FCC Facebook group

<img src="https://lh3.googleusercontent.com/JrsXZRlkclhI4XJwUvktQ2HqBwd_je4p3Vgo-VnNj_s6m_EXwvhaY9T449gWpgvDL9fiFSvjbrglzu2XMqoJ7oxap1R-IItxaNiQe2VD9aLpfBLIxn0Lrwv8I80eANG8re4h05Tr7w8OxVz8IbvtY0I6IKDkAyogSJbkz4lWr_hgOrolbEQn82c8fmCChI1rrZJlaFfXUnxLi8ZfffFZd-8wGY4tY-O0YIkXGaRiti6Hi0B6alJkcgmCnpYnWgDfaYHkgEWa4liLVTX88i6tVCfD5-nWE-EZ3PT1AAeBBTCtbau68TiIipWQh6_WETEGKOxq5FbbvpZh2N5GOi4jN_1szWu2nRDRlA8Clggf4sovKIijHyrLMFGEUqJ4iaYmkYCeA8-bBWgaA6zwQA8yv4JGI40TdlN6_4Pm4sHQORu9Exp_naDTim-8bdpCh2LFHPEv6qgGXfdmOaitoDsUiXv6_Ua_dcB5RvRde_Rwx9lGGjeJn68V6rtanbyVrfTzCNMbr63DZF3tdCSdGIeLlHXZ7cmtnCnZiusYP8IqpqiNn71uL6i1Z6H1vMW15Kh6S6q1jQiNclAyzbOASEz87ID_Qitg3CdoojWmX5UgRKmDUs1PkST8Vg=w1278-h577-no" alt="Free Code Camp Little Elm">

**Link to tweet:** [MightyJoeW Day 80](https://twitter.com/MightyJoeW/status/856383171369238528)


<h2 align="center">Day 81: Monday April 24, 2017</h2>

**Today's Progress** 
- Added updates to FCC local group then continued progressing through the [FCC beta](http://beta.freecodecamp.com/).

<img src="https://lh3.googleusercontent.com/Qmoc-kAe427WbA4lFqvxmBob1SBAIwe35K1JkMSNHKEpapLSCngERsypX6e4KCQo_kDtMlwbLgwk3Sbb72CqrKn7QdgO_rfpJGhr5RwkjsYlXKYMBYGn1HWQaZPXfdyJyqdUvzetqnKGWXHF4ZSeIbICD90ooXjFKhOmHix7sw7eFaYd_dE3yIe4vdcc9Hc73eyoNFsN4SWTB-4a3NRzmOFTXMAPmNHCQ4rxHoeVoM2Y95j-9_2d7cYJdbpLOETDk6iAsA1Swvh1sYHgzTXhzr1Y2597d3nPRCdj2us1hZd1au54NkV7xTVY86XJoNx6D8KVgjjVfnWk5Hmy5xhY0caFFD5rsauNGGNbouHcLaWomRlsi_Rp6f1TS94QycrjNOKetFEgIYp3LSusGBYY0XCSO9bFcxPWWQ3JWHQrocxH79X0tnyVSUGNP30qsA8AmSMC_zzln5FgNckY8Gs0nkiZHGsbobEz8QerRzGMcRjcE4H-Eg4onMMJdYOvYfF8ONL5GEmmEtq9LHjqN4nqMY9WE7iTpJ2jDmvmd1E4k1SZ9R9nHBVq9znaoJKpfLgnZLOlw3JfRrQO3T5ro2CQlqd5j1FP2se6PjynsiagVKGqgO_hvsn60w=w1145-h627-no" alt="Free Code Camp Beta Landing Page">

**Link to tweet:** [MightyJoeW Day 81](https://twitter.com/MightyJoeW/status/856694151697530880)


<h2 align="center">Day 82: Tuesday April 25, 2017</h2>

**Today's Progress**
- Continued progressing through the FCC beta and revisited some CSS in old code

<img src="https://lh3.googleusercontent.com/s3yFQoIn0HD49vTGpFs8QjRTqS678hA5JTIZNU51SekJj04YbKJ7-o5ZQ96VNFJFp45Ec06K8Cv4a2y-oEAc6TNatq40Bms8WaIWLrhaeomXjzjqwoyk3TxewBxmLW9Sx7sn6CA_su_xM_n_D9uUKFr2syYFkU34sKH9hBJnwhuJNSdWnuZvDY6rR4cj01A6bFUgspPDpmpFlKzCsSAmOR1S9xaJOvHQ27Dgq991agHXrn67eetdLlrlcM2Ffh0pWkPPhkt5y5b0njTWLhkEZOtsjQ7aO76bWkZcFEAHWxpJgkUttxZg2pVWJFcEwQB3X53owyFr8WUUltC9vlZ6OUlrX2kMHQHrL3tW0z-zcT-TlbbPMrP-X5tOAXNJbDBxaNG3VnCq6kwgTTnawlQMqXVqPkl9Y4BaWaBES5ID9fL1DfIw2J_dlkUiTD3VphWighYFecb76lKz3o72MaUnCWNVH9mP5-Uw7CZ4ZIDRqrntqrQxnYMrAc2stQ8sjB62UJkBcoJr0Nk2HYx8-GbO1VRSCsSkuaFwBdtQVSej_CB9lD7bYja6hb9JydXmeIo_VLbnlw4C-b-3O1LKsH4BmulRHmsHAvWgHoheyCzOJaVi4PagEZWtuA=w1152-h627-no" alt="CSS Fading Ball">

**Link to tweet:** [MightyJoeW Day 82](https://twitter.com/MightyJoeW/status/857111509780103169)

**Link to work:** [CSS Ball Fade](https://codepen.io/MightyJoeW/full/eWgWbr/)

<h2 align="center">Day 83: Wednesday April 26, 2017</h2>

**Today's Progress**
- Finished Applied Visual Design section of Free Code Camp beta
- Created some CSS animations in Codepen

<img src="https://lh3.googleusercontent.com/M1fv48Ai5CFi_czAfOWRoj85uFhO4BB6gyfMfcTl6i-18AAlsQ0LTpGzGTLV3sJiwu6bleJwBWSTgWn3logo68fgVHoEhQU9IhoaosVh5bZII2ZeAENgSPEzd38sLeVJ4qd57rhkCHnGhHdUugDOk8P6SOMp2BaRMzF6zurGInd_C1kFPd1-LBdUs2bgPCO-zV_P2_73WW4TU1EcPaICDtJHVHyi4_BzAZNcReV9RsZ6sauP4DQJcdHW6no-Fsh-vwvNfWk2CRavkSm2nDFdEU13xEHf3Hyicdu0YZ_0csvT9hERZk2i_VSAgaUOhJKVXTN8nTVfh9GBUY0HXsc6hWuaMUJyKGTMweDA71hFTeVKSjhRCDfmWh-Bz5NTXCDAjFia8uw4V4kPPwlcDODTK507KeuJhi6-47t_ar1_v0gZrm0hUeeJJIi4j5x0hpnC9VwPUiAgf5svf9Go3XbAmtiIbj-NP7uIGo_8jAw689fmA9IrRLKV9Q9vYsvLpzSX4VTIb8e_QYEZKaFnq0eDPFxdsqv5vtnnIob0T-3SKGbiI7mV_EJmv4iLNPHStTpvI1D7PxZENPxQQoc0ymEnLGiiYFMOHb46ZHvroBY95GqWzxNeBy1MJw=w1146-h627-no" alt="CSS Bouncing Ball">

**Link to tweet:** [MightyJoeW Day 83](https://twitter.com/MightyJoeW/status/857461961486946306)

**Link to work:** [CSS Bouncing Ball](https://codepen.io/MightyJoeW/full/qmRmww/)


<h2 align="center">Day 84: Sunday April 30, 2017</h2>

**Today's Progress**
- Started on the Build a Wikipedia Viewer project at today's freeCodeCamp meetup.

<img src="https://lh3.googleusercontent.com/1qcQjWFdZAzkOQ5N3i0E-B-eLI2xETAsUUnQ0c1pwJqOPMWi80BvzbJKwR-mGCiUcy2WSAUm1tKCcG4EJfjQ1kBB71eO0bf_nU0qpDXUC4XumLHcLg8P0Uk7zil_4CYMbp-3g4TDSZLAI8lCn68z86lDSL-j9sSPa3lg0pVqhjZ9OpNg4a7qzhFCTvkyBr-l1dUDkzOt-j3fROUGOwPVbsi1cEUsCth0aoOYZWFgZG6czQHJp6o2u2j62-cPtiYkrBLjNXUzD8ngBAnnksiKM1KIa4ZB0wir6lrYJ27pJSUAJK4Yj0uby-F0K1B6gCixRlbu7ZSoyVnAxczK6JlzdYj3SU2jraAlWYiepURKjCqdBZeYNPLKW031aQ-ScLFAAyWEGDqki0R2NZaKAOZWLzZ3mDFuSS_h4t-EVO8CrERejO09OjlLJKQNylkhKkrFDX4wcW_mRU6FVPL0oCggipGb_xpBPFRdRsH42BkhilKjPSF2SmBgX4KMTYWFdanpFQId0wwssIEnEN_pKKe0mibfuUAKHUwGCpr8mcfQRzhCYnwlRSaaZwgD8SelkGeBhg17XFd1to2vu4Iuz9G0814fSgPw4CGc2dfykH0SNykOcdcJBnxfRg=w1278-h254-no" alt="Early Wiki viewer">


**Link to tweet:** [MightyJoeW Day 84](https://twitter.com/MightyJoeW/status/858789779823046657)


<h2 align="center">Day 85: Wednesday May 03, 2017</h2>

**Today's Progress**
- Started HTML5 Games Workshop (set up background image)

<img src="https://lh3.googleusercontent.com/KqR_wxRDNl55cNWWYnh1KxJ3lYC9ctZ8A6Y1EKnKu_yEBrCrLabS_MwpjULt_EgXa5cDDWtSPMpi1S5URXOxrTIXz-osDwiGbapNEUafhPxhwTvzfVxM9dQUTkQTJgfWyvAaykSbFzu9Ncu5yJfEOL_ZwCUn8KeBwa9pf28oRBT3txZiQ1XSx3DUCT7MufZgv12JZsrdMzi4jtEbEaicuMlyVoJNUcV8MQu_Pt_i-ux7q8SM74b1KjADFKX-zTQT5uYSQc5SiosaMR7Qn3PyEDMdlgE-lHLKwAxLUNktU5_7N87vaP38L1l-orLCUmvFN8d1s8pfUFHBbtRPAjPUu1kOGEtJcKZuzmA4j9CRzeGlD5Cj83tDCDAt7-MAGwm4ysuy1ALYFp0-S97rhtlPJQIOza95qGUcZS7trZxWmLr2fU8uzTDRRzeh0qbqU_4ywY4r61jkpPa1jhBWskPHM3NXjnlM6YbXlPf31wCsYU_uoA_v0h2Hzh4mpehnf0WsxP7v8b09uaEQtsUJkvu8SoKX5iQWHsxB63OFpZKfoLkp11Zwwrx7xFvnFLAT2RcZ3ohLfWpCMg9igaJRu_jOB5ItwK4KMkEmbGus5nXONNRAnhbrxPSD5Q=w1274-h617-no" alt="HTML game background">

- finished fCC beta's Applied Accessibility and Responsive Web Design Principles sections

**Link to tweet** [MightyJoeW Day 85](https://twitter.com/MightyJoeW/status/859953122550185984)


<h2 align="center">Day 86: Sunday May 07, 2017</h2>

**Today's Progress**
- Continued on fCC Wikipedia Viewer in today's fCC meetup.

**Link to tweet** [MightyJoeW Day 86](https://twitter.com/MightyJoeW/status/861399428938203137)


<h2 align="center">Day 87: Monday May 08, 2017</h2>

**Today's Progress**
- Continued working through CSS Flexbox section of fCC beta.

**Thoughts**
Woo! It’s been awhile since I written a thoughts section. Unacceptable sir! It’s been a rough past couple of weeks trying to code. I’ve missed multiple days as my focus has been divided, so it feels great sitting down and just straight coding. 

I decided to start building a new page while going through these fCC beta lessons to actually apply concepts I haven’t been using regularly. This not only made the concepts easier to grasp, but it also allowed me to get lost in time while coding which is a good thing. 

<img src="https://lh3.googleusercontent.com/paWmKZleYZ71GT3VpoYe4PTva-RqR_ub4ysHMZxpxiMCCudS9btD8hM-vIRx6FBIiBhghSm3pa2zxP-73Jv8eLyjJC5kIkg-rNJTm0hjzTcNHxl8F9Gr_jAVweADQJDWFS578dqOTSnUIdZCqIIMtq5jFtYU26r7kjqvGDtq5F74jJHyb22tQP2cYu27S8B0I6iwCuQskvLH-hkmxnZNdGxLHdvQSEJZca7vYTCpNj0A0LYClid4g1dKoVo-r2CKoMZIMx6-0nSI-gXyS44BhLwivGup8Tbiu2Ap31PiEzNDntT_hmm6MPNXvCb_dw32mV-Xkx53QchYi4OHmFm1WEr_J1jPMRF8rjshnJaNibb8dPdGP8YS_PJKppqIvEN0OaT7gDdkZ8ki7SGQuZNqkrJVNcQCoGyRIfGiY66GwsCg7oxkOTOIjcTfPI7TnJ2nbi35-iJgKnJqbWSrA-j7Ipay9NC5n8s0mYLnDnvtQ7dWnKqwisi1RscNAXSxQuaLN1ErFmw7JL85nYObe-FCet34i89_X9T3WVOjI2TnsYukdTDnwuZ_2PT0Y_bVJG0Z_HsCq4DvXn3xSQ1yJ7CUqyKEvCWXRnJxumSl0Q1LqXwvf8qoT0xlng=w1265-h617-no" alt="Mighty Flying">

It’s a similar feeling to creating music. I could sit for hours adding and tweaking sounds, panning instruments, changing chords, etc. Coding gives a similar feeling of progression and creation. 

As I continue through the fCC beta, I plan to continue building my own pages while learning opposed to just knocking out lesson after lesson. 

**Link to tweet** [MightyJoeW Day 87](https://twitter.com/MightyJoeW/status/861779915514839040)


<h2 align="center">Day 88: Tuesday May 09, 2017</h2>

**Today's Progress**
- Wrapping up the CSS Flexbox section of fCC beta.

<img src="https://lh3.googleusercontent.com/NgxCa-TWL1mokkpA71-7LqcHB_0o4IuDmsEFe0Ig2Ppv-C4wU4ittZ3gyOkO8AVwlBiHJUcgXJF2YEstIf0NGQ7BAaDaTHUPm67jmXNUuP9j8550E0fZA_dNi5V8c6-F1qdrG_EpWgWJ1BtTmNxHNE4LdZxuffWfdYX2b8N5BYpRvELuxthWBIA-FqrivVyPboEX1aRjp-U3eUIfcixl65YVRC-Knkntfhnn-6IT52nSHkQwMZnNFSBhqo4mVu8g6OLJ9wWYlko8xRG_EkacPVAmB5bgEQpteOwkapKmPLqkHdj5n_yIU2t1RrauErnD9dOvNcl3z64AbabCyfZXSL-O9x7QpxJe1PZ57HIqdJPt1FJakMcfyMqY-9cKLgwXe7E__zS7FpKOe9GC-Uv0ue9-ku13Dr1mLo0dPd3mpPIw5CNpg85fiE26hikwc1CDOne2PtieIiYPzNYedoIkD_EAZPJe8uXycVq_1_OPj-HTN7vXJ_iPp0Dy1-tx6884Oa2xTpjDwIMVKRWNKX_SjqLdpady8_YghcV-mkCPl7xaUXUDis1JaH9JXSFwziEVm-QZVItczAsCdKVZT3ZPW_QWehMCWPZw71AAbSeEoY8R_dkAoRupMw=w1265-h611-no" alt="fCC Beta CSS Flexbox">

**Link to tweet** [MightyJoeW Day 88](https://twitter.com/MightyJoeW/status/862086297640472576)


<h2 align="center">Day 89: Wednesday May 10, 2017</h2>

**Today's Progress**
- Finished CSS Flexbox section of fCC beta
- Worked on new tribute page (this time without Bootstrap)

I initially was confused when beginning a project in the Free Code Camp Beta, but then I opened their Codepen & saw the new Test Suite. I'm digging this so far :bowtie: 

<img src="https://lh3.googleusercontent.com/hee928uMWQi8vXABPyaaM2Y46qPr_uVC4iD4afDxOSTaTHZiz_SOzCULwvT1tq5onWXwbIjGSR-1U0gdmMkCo1e7QNpsbjhs7buj3NQE8v7i3CI7WIhLq-fIlNp2UKZfA_FsWhCOq0ompLy7MrYuYDhYhiE6SId-oBtoRzBZUzPxCt5tN97E89JEI0hZOPNdiFNEVmQ_YXNnVT3J5xZHqw6sy30Fl8XlPPRvnhqN87oeXfsRm1-VBjV5BiuOy4RZVziT0aWSp7-8KsBt5Wia_Ng-pNnyJTUxnSrKL1apcwKF3C93-qVPY8TucvG5LzG6KqQTcrOuNfeMLIkQJ6ieqFYXc3dvDVM9CKVe4xqblIRdlIOSZPPPGJSixzMIxjVXTOLaZ0zO6pcv6x1hEaBcrap-tOYapR4zU-CBqT_DZJj_gkr5CFG2c9gy2ivHc1F78lOyqRhBbNxtI7_4FpchmydZgt0qzL8HnN3WcohUspyod5EfYgeGQAaYh1RqMe5dgUnWvMcvBOSm0P6XPGZmJjCl6c77se_zMkQJgp06YmKt16QkHGbWLwZyTTuwwXKm4DJ3OBgdI0zOGdjm9D2YClEVKGboV0RAtyrz-b60CFOGFdfx0xZCPQ=w1264-h627-no" alt="fCC Beta Tribute Page">

**Link to tweet** [MightyJoeW Day 89](https://twitter.com/MightyJoeW/status/862508267515281408)


<h2 align="center">Day 90: Monday May 22, 2017</h2>

**Today's Progress**
- Worked on landing page (based on a Kajabi page)
- worked on fCC Survey Page assignment

**Link to tweet** [MightyJoeW Day 90](https://twitter.com/MightyJoeW/status/866861564925816832)

**Thoughts**
Good Lawd! It's been A LOT of days since I've sat down to do 100 days of code. Do I even remember how to code anything??? What’s an h1?

<img src="http://3.bp.blogspot.com/-XrfnQW-QVX8/T2TGxSDAu2I/AAAAAAAAAD0/OW_6YK7F24I/s1600/11177744.jpg" alt="Confused Jackie Chan">

In all seriousness, it has been awhile since I’ve coded regularly. My time has gone to other things, some being understandable (my current job, revamping my backing up/storage procedures, fitness) and some not-so-much (NBA playoffs, naps, etc...)

I have still been connected, listening to coding podcasts and attending Free Code Camp each week, so all is not lost. I just ran through a [10-day free bootcamp from Skillcrush](https://learn.skillcrush.com/skillcrush-10-day-bootcamp/) as a quick refresher before picking up where I left off with building a survey on the Free Code Camp beta. 

Also, I unexpectedly have been able to use my newly acquired coding skills at my current job. We’ve recently started using [Kajabi](https://newkajabi.com/) to help clients build their marketing funnels/sell content online, and my coding knowledge has been a tremendous help. Kajabi provides an easy point-and-click process of building beautiful web pages and pipelines. Being familiar with code helps me understand what all is going on behind the scenes. 

I was asked about removing a certain section of a page (which was not possible with their editing tools available to users). I was able to do so using the Chrome dev tools on my end, so I just had to find a way to make this happen live. While chatting with support, they asked if I knew CSS. Of course I said yes ;) He sent me steps for a possible workaround which I would have had NO IDEA what I was supposed to do had I not been learning to code. I was able to successfully make the changes using a CSS workaround, and needless to say, my boss was highly impressed and appreciative. 

Here is the code I used.

```
hr {
display: none;
}

.checkout-login-section p {
display: none;
}

#sign-in-link {
display: none;
}
```

Going forward, I anticipate using more code at my current job while getting back into coding more in my spare time. I was able to successfully wean myself off of watching wrestling (don’t judge me), and that time will go to coding. Not sure I can cut off the NBA Playoffs this close to a finals rematch that I can’t wait to see, so I’ll be trying to wake up earlier to be more productive. 

I’m well out of bounds of the official 100 days of code rules, but I am going to finish these last 11 days for me!


<h2 align="center">Day 91: Tuesday May 23, 2017</h2>

**Today's Progress**
- Completed 16/16 tests for fCC beta Survey Form challenge
- Working on CSS for survey

**Thoughts**
We're going streaking!!! After some time off, a little 2-day streak of coding feels great. After I finish adding CSS to my Survey, I’ll be moving on to the Build a Product Landing Page and Build a Technical Documentation Page challenges. I’ve already done a portfolio, so that will complete my Web Design Certificate!

<img src="https://lh3.googleusercontent.com/zbnJVSQ1rVVTCp4oAkhVoXS7Uzc6UpTlPFP39eRqyt9hWzxyKlVo4kWfNbgja8decaJzZc6g5LdfcSXI4Bbb56AUCseUQYTOVkf92EsIphVx8NaXfDTuPIxOPOsapEsiORQOFdHW3qztwUpJ6PKBxuH3Ee_jbv8FhcjUMs7u_m-CKdNinuGg39Hf02YptpSTgqcxb4lgCvtGJes9tyLqYE2uLEgMt0neCxy7zllg6uVoXVtJESwR6Cfrv9QYKNuapXaG3IRsVssxk4MFwpwsHKlSPxN3V5MQ1WZgRTaCyJ0lsCk_erCozvObHUiZclULpHAg9oKyv2Yo85t6lc6BSDXPDiTs1I-U4aWUFUtubygtvv5r1Wx1lVizBovs3x4_MWtObjB_Qdig3Qik23N12x6APhqaExlAEDlfxT9PDhvWwkMiBUXjr76yRazGIXbP61-AwGN4bSjyGhV5laIRYixENpGueVPuPMH8rD-Ac6_np369g6Fbb4Bq27mLWHNTUpvTQvAupllf45XmgtgakCsg2Hqb_GGKUW-IV-XqlvUyDcIrNnwRwG3gtxBr2KhwvALh3LjVhE83FssdQjb1bO2I5nPms86TJTYwDfBRrT6W7xZh25iGiw=w1276-h587-no" alt="Music Learning Assessment (Codepen)">
 
Then, I’ll be in the Javascript Algorithms And Data Structures section of the freeCodeCamp beta. Javascript seems to always lead me somewhere else at some point (usually from being stuck), but I am going to stick with it no matter what. No, I will not come play with you Java! Sorry Arduino, you’re going to have to wait. Javascript is where I’m focused right now, and I’m going to have some breakthroughs. 

**Link to tweet** [MightyJoeW Day 91](https://twitter.com/MightyJoeW/status/867164389886926848)

**Link to work**
[Music Learning Style assessment repository](https://github.com/MightyJoeW/music-learning-style)


<h2 align="center">Day 92: Wednesday May 24, 2017</h2>

**Today's Progress**
- Submitted Music Learning Style assessment for fCC Beta Survey Form project
- Started on Landing Page project

<img src="https://lh3.googleusercontent.com/XmS6q9Hh-Wipxo5Hhnw9-YjjAz7Hj1e3zyPPwn3RK-6q1-Lywp22S69zq8fE1BojqAzbZ-fhQxYf2sqIIfkStibw2YP1ziOldVXF-_5nJ5gXDwZa4pN0IpJOHRxZiJy2DUiDHh8XOhqu9HZKiMdWLSQESXDrS2ZTQj0IP3nJwQ2B1rJbl1-sZLJT3srSciwPZvUCjDxLMOPi_pbbY2dvmzhrN1Pt687ZqwvNitKy8j4dkiCG387ur3rJYohmgPJ3U9aFrAWyJuy7vcgxkXMKsRelJZDiJIi8cL5JzQ1DefrF1csQsupPIOa1wJ7EgBd0xJxwvV97VR1hZZrRw9oEbwGq4WTFi00Fmpg6F2h-KO_vm-w6L6QO19iMaVNazaELd7OimKs7uf1KpXPdGzMAI0_6yiHpNkEVEdca0SPJ49lqdMs4O74y7abqydMneSLSBEH9GUiZMZUvjBpVOlNbGbNr32seGFIPpaJzWt7-eEhv1xJRCFMnDp2X5a7rL1qwaWnvGtZUhiSDRy8LnMJonlAkBGatPhWXK_Oq04_kH42OAhy4aF-nJKNsYhBIfN0amF4H9V4alUnFK4e_HI42wrDaqurgQup7MHMl5hy7vatBIu6LfdJQmg=w1135-h627-no" alt="Music Learning Assessment">

**Thoughts**
Momentum, baby. We’re going to keep this ball rolling. After finishing my survey form, I got started on a landing page. I’m actually picking up on one that I started some time ago, but I feel l’ll be making a lot of changes. It has bootstrap which I’m not sure I want to use here.
 
Something else I’ve been working on this week is doing everything in the command line. I want to get as comfortable with it as possible, and the shortcuts have been sticking so far. Man, something about making things happen in the terminal makes me feel like a Certified Coding G.

**Link to tweet** [MightyJoeW Day 92](https://twitter.com/MightyJoeW/status/867508480336375809)

**Link to work**
[Music Learning Style assessment submission](http://s.codepen.io/MightyJoeW/debug/OmvVVJ/mWAoNbLxXNYr)


<h2 align="center">Day 93: Thursday May 25, 2017</h2>

**Today's Progress**
- Working on Landing Page
- Started Javascript Basic section of fCC Beta

**Thoughts**
I'm about at that point with this landing page of wondering should I be using bootstrap jQuery. This happens about everytime I try to build a page from scratch lol. Trying to keep it simple for now!

I wrapped up the day with some Javascript review as I get closer to resuming my JS work in fCC.

**Link to tweet** [MightyJoeW Day 93](https://twitter.com/MightyJoeW/status/867865287114321921)


<h2 align="center">Day 94: Friday May 26, 2017</h2>

**Today's Progress**
- Working on Landing Page
- Continued working through Javascript Basic section of fCC Beta

**Thoughts**
There are too many things that I am wanting to do with my Landing Page that aren't working with pure HTML and CSS, so I've made the executive decision to add SCSS and jQuery (dun dun DUN). I think I'll be working on this Landing Page for awhile.

Yesterday, I worked on html and css in the morning and found myself later thinking that I need to be working on Javascript too. When going through a curriculum, I feel that once I get through all of the html & css and focus on Javascript for awhile, I start to forget too many concepts from html & css and vice versa. I'm going to try to do html & css in mornings and Javascript at night to stay sharp on all 3 going forward.

(Later that day) I ended up working through some Javascript exercises and had a small, personal win! When I got to the Stand in Line challenge in the fCC Beta, I immediately had flash backs to when I first was learning to code with the [original Free Code Camp](https://www.freecodecamp.com/challenges/stand-in-line). I remember being stuck on this for days. At the time, I knew what it was asking, but I didn't know how to get to the answer. I didn't want to look up the answer, but finally gave in.

<img src="https://lh3.googleusercontent.com/cCh5erC5AW8M-2z72KiMFpooD7-Bdho2DMnGc3Ad1lXsXSxi0P6C78VdfvpuZbao1HSRmXT9BfZicNpaScHpLCHoRp0_fWCbgyeOGKltz9UmGWuWy5XxxPOyGyOkIOJSyleUnuX27-TF_UqfAKbNjcxNLeNlKSgAruCkKwp_FqfNL5RSPgl1ipKXgB7DIcUjsZy5uikxJ27S-3O58sbttKxawisO1pfV_bNxVZLkcJYGqVQYjxDim6GZKeIvjBhee0EMZnmaEhvbTMqG3guyPLjZ9VlFdzwcToXfGbdMEF3aQV8Fn2RjoNACYM9JFAKciqfQ-JmZtt2fHUl7k0q0Dmoo0XBnKDCck3eXqZrdaePvyFk05sBp5Vza3cjxPlE5AiHrAw6QwdUfkXvq0fRuwD7MngEy7Vwwx7pCq8oL3L2bexM8XqmYJfnHH4-oZuDilF5IW3JUN2DDe4goPyZPHs08zka1sEibVHE6J1ak8dUIQPTkYD0PLATuWGJs4l5YWRL3dfRABfgwU4LrM2FSthg7KBapt9cJQzQPcopn_a_hGR_3WvOXfmEH6Tnzcn3POu226dz12H_tBdKMhijIlJYR1cZ-KXYBCa1xHLgpkp2HAbYPwtZYOA=w395-h475-no" alt="Stand in Line challenge">

This time, it was much clearer what I needed to do, but I still wasn't completely sure. Some of these concepts are still hazy since I had been away from Javascript for some time. Although it took me nearly ten minutes (on what should have been an easy challenge), I was able to figure it out! You don't understand how great that small moment felt :D But like all champions, you can't celebrate too long. It's on to the next challenge.

**Link to tweet** [MightyJoeW Day 94](https://twitter.com/MightyJoeW/status/868263743154778112)


<h2 align="center">Day 95: Saturday May 27, 2017</h2>

**Today's Progress**
- Working on Landing Page

**Thoughts**
I changed my mind yet again. I'm NOT going to use SCSS and jQuery for now. I'm finding work arounds for the Landing Page. Plus, I need to spend more time with the basics. This has been a fun process though :)

I have run into some issues passing some of the fCC Beta tests such as getting the image in the header to display correctly. I'd rather build the page without an image in the header, but I'll keep working to figure out how to pull this off (hopefully without having to look at the sample project's code).

<img src="https://lh3.googleusercontent.com/9idrOYfFjMpb448gyPl-6Ne9Bv_oKvifTnEs2NkaPUaxF1a85z0Zj0nGMoOO0CbNHIs4tPSEDCKIhyGt4kxfGAkk20QNvWTj2gKjrYzfRupPppqFM9VyPUBNS-N0fdKiolEl40vknFjneRIWrlkEJ1fXcERymx3wwWtkrGhpJRWx9dVmwdHw5Y_l5K6iHyf5wG8gKaUm5siuVrhpH3AEV-LauKJs0ku2WajO_tQxDVHRdIEBv44UpyyTnf9kELx3S1r2jGNwkzGiFGTjAx2gW8W_HRSuKg1WRP_sEvmW0KeBj77S5rtkfVCXkk_b6hxgCqtunDKj2Z0oSAkmewl9XhWpbWTJMgyiiYFqzxtDUUYPiwgX6ehJ4csroHTT0z7t2gdHg8l7nD3YfNHgtoczwTMifqYNVTMK77HDrJIeZ8kGyHl5JAJ-Mt1B6cl9kIryZie0iQIsomLvXzdaL-WaPp_rgZ53h0CqGgqnWYE1pYLxbRS4zu8BWjFJBp0SmT0OIywXUQtoU52ecmc6lbKj_3TjN1TVmoY9PvMw1iH73I_Tbn45tq6B3ykSm46lMFjRW445TmoNV8zIKDyFC7j14855BmAi8488dmeu0s6CMYNzsuB8WXsAxg=w1278-h626-no" alt="Games and Keys Landing Page for fCC Beta">

Gym break then will hopefully be able to dive into more Javascript later.

**Link to tweet** [MightyJoeW Day 95](https://twitter.com/MightyJoeW/status/868499899272376320)


<h2 align="center">Day 96: Sunday May 28, 2017</h2>

**Today's Progress**
- Worked on Basic JavaScript: Counting Cards
- Free Code Camp meetup

**One** day after deciding to build without any frameworks or libraries, we started building a landing page using bootstrap _and_ jQuery. After quickly seeing the power in both and remembering how much better they make sites, I've changed my mind again lol. I'm going to roll with bootstrap and jQuery for the Games and Keys Landing Page.

<img src="https://lh3.googleusercontent.com/EvlC9fWcDuE_rqTGtQAFS9i4cwNpoDsCeDGJzm7LPuZI_uSQIXST0UZHHyXZ7ju3dWgUqCS26uJZ5J2_uPJDlstcMx77-pl_ekJPxfoXwrmhcdIFOUjfnSSjmcu5bbcg6UFMSU8cmOioZWvSuKCXBw3InYox0ElbxwQZUv_3_pN3vxfl6I8wqcM0fmZ6dIgDlbvT6lEXfbnCcOjErAtSp5eSfvITGjUP4jauDNuCJAHBNx84MECibBgziIl7SXwbG8eNN8XbSgXySgYiymmpCLZ9SuXAdQXIOHfwl4jKxw7fGwnZ8s422q2U95CxXAWWiI3sYLgbqxBdMfiYwVivObf0txPxVa-80plOlPnF0A6rcgYZA-YYxybOdix-F195lI6hF-5uhTbxII5NGXbz9sLaqJBRSAGru5xddguzCeFCg5NcjrDYrvH6ap85tqlqHeLIUNG1lUVpxN2_8BEky8X8ei9lsqbmL2DBp6jZBFojJFrym7wmL6_Wgt9oJO-KlvgWQOlA8NH8_gjp0pnSvyvQxJMDAUlp1b_vcFW8gl7xOqKeM7i85fE_WDqRE_azqeBRWdiyBPjgQDxUq0thEZZ0Isjs3P8wK6QMDwVvFB_rbMyB_JgoGw=w1139-h627-no" alt="Games and Keys New Landing Page template">

**Link to tweet** [MightyJoeW Day 96](https://twitter.com/MightyJoeW/status/869040491207290880)


<h2 align="center">Day 97: Monday May 29, 2017</h2>

**Today's Progress**
- Continued through fCC Beta Javascript section

**Thoughts**
Another late coding session = Sleepy Jones :sleeping: so this will be a quick yet impactful post about a man who has been fooled twice by the same concept.

I can't believe I got stuck on the **SAME** mistake from the original Free Code Camp challenge [Manipulating Complex Objects](https://www.freecodecamp.com/challenges/manipulating-complex-objects). Even worse, I made the **_SAME_** mistake of forgetting a comma between objects in an array. 

<img src="https://pbs.twimg.com/media/C7fkiSpXkAEEdsn.jpg" alt="JSON Missing Comma">

I better not EVER forget that again. I'm going to have nightmares of arrays with no commas :grimacing:. I vow to become **THE COMMA KING.** ,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,, `#TheCommaKing`

**Link to tweet** [MightyJoeW Day 97](https://twitter.com/MightyJoeW/status/869398932421578752)


<h2 align="center">Day 98: Tuesday May 30, 2017</h2>

**Today's Progress**
- Continued working through fCC Beta Javascript section
- Continued working on Landing Page

**Thoughts**
Oh, I didn’t see you there. `console.log("Why hello there, World.");` 
 
So the question of the day is how does one spend day 98 of #100DaysOfCode? Two days away from a triumphant celebration of persistence and excellence? And how does one feel with all of this new knowledge?
 
I have a feeling in which I believe I’ll have the rest of my programming life. I feel like I’ve learned so much yet know so little. I’ve heard many guests on podcasts speak of this feeling including the dreaded *Imposter’s Syndrome*, so I’ll continue to move smoothly knowing that this is par for the course. 

![Par for the Course](http://metrouk2.files.wordpress.com/2014/04/81182_3ds_mariogolfwt_022013_scrn01.jpg)
 
I kicked off my first coding session of the day working through JSON problems in the free Code Camp beta, and I spent my evening coding session working on a landing page. Seeing as how I started Free Code Camp back in January, I should be WAY past these sections. However, I’ve taken my time with the process while also exploring different programs and languages. I’ve enjoyed diving headfirst into the wacky world of coding, and I’ve taste-tested just about everything that has come my way. 

<img src="https://lh3.googleusercontent.com/DlQvKUy9INo6Tjz_8mdwzb-Rtu1iDavxdfF1haElQIW9zRB1BYSQ-Wn--DNKBEuU89AiIPNZYrhqOirQcaxwZECEtlAW9rh61IZm8IVxzZ02EAkg-ULwaCY3TWza11E4h3q91VWrFymD8ItSXtx6LLrf1RxaAVMJ2t_06SdRVbIVmtRld4GCUJj8dJMZJ3mjDvEVTD_cVfqNn8vO4E211171SKagmgM6agw8n5_CT6FsVCS2bdH_FnxVWUv9Oti6cFjfrbu4ZAxhSLSt11bCaSCb-hKEUBKMTchiFiFAAo8NyhDec735xy3Cw-e_15gvMPzElEH7kiPkGU19uOfbi4MtzpJAKH-BW_onEcjqrf5ekkjzqugX4Pi7zwujuCFTEem3EYROJo81AO8-TEwR4i_riGUep0RqMU1uAb47iitzwlBW39LHb4ES2x7xh5zDKBAEHyWqeKopVn6wwnx_6WVYE20M-GNfsIYk9Rxeh60KycgaBzXTnkO1wngOK5VtjoOqV2W0JhuuN19VeXtPksVoy6CPXHREFAlzb6R5QGl9qFzB8_GorsDY7DxAFf8taDWVZYZZ3uiINLSAzEPgE0pbOTM1jS7E9rzawYosTTV0Zuq8o_Isrw=w1194-h627-no" alt="Free Code Camp Beta - Basic JavaScript: Record Collection">
 
But at some point in time, I believe one must focus in on a set of specific goals. When I’d get stuck, I would use that as an opportunity to dabble in a new language or play with some Arduino code. But I’m on a new path to stay focused on front-end development for now. [Free Code Camp](https://www.freecodecamp.com/) has it all laid out for me (along with the [Web Development Bootcamp](https://www.udemy.com/the-web-developer-bootcamp/) course on Udemy), I have all of the resources I need (including a live weekly fCC meetup), and I will NOT use difficult problems as an excuse to switch gears to learn something new. 
 
So as I work through the fCC Beta and catch up to where I left off on the original Free Code Camp curriculum, I plan to work my way through both, gaining more reps and experience along the way (plus, I’m not sure if the beta progress will be saved long term). 
 
So to everyone out there learning, struggling, and succeeding, keep fighting through it. We WILL make it, and it will be dang worth it!


**Link to tweet** [MightyJoeW Day 98](https://twitter.com/MightyJoeW/status/869780685535404032)


<h2 align="center">Day 99: Wednesday May 31, 2017</h2>

<p align="center">
<img src="http://i3.kym-cdn.com/photos/images/facebook/000/094/422/tumblr_leretcb0Sa1qfawn6o1_500.jpg" alt="Funny Code Meme">
</p>
<br>
<p align="center"><b>Today's Progress:</b> Spent time learning and implementing advanced Github Markdown & HTML</p>

A glitch may not be my problem at the moment, but markdown sure ~~is~~ was. A combination of things led me to wanting to give my Github a makeover, starting with this very log. 
 
We used Github a lot in our past Free Code Camp meetup, and I have some exciting tech events coming up. You never know, so it’s best to have my online presence in tip-top shape heading into these events. 
 
But let’s get down to the *real* reason why I decided to give my Github some TLC. **Richard**. Goofy, irritating Richard from HBO’s Silicon Valley. Well, it wasn’t directly from him, but I’m still laughing at what he did in the Tabs vs Space episode (I won’t spoil anything major. I promise.). 

<img src="https://i.kinja-img.com/gawker-media/image/upload/s--pjpRvNqK--/c_scale,fl_progressive,q_80,w_800/v9uxhcf6didf4cgsakmd.png" alt="Image of Scene from HBO's Silicon Valley">

Anyway, the part that had me thinking about Github wasn’t even a major part. Some of the crew was looking at the code of a Facebook worker’s Github page. Without being around developers in a job scenario, I don’t know what exactly people’s process looks like of using Github to view or clone someone else’s code. Realistic or not, this scene was enough to make me want to give mine an overhaul. Enter **_Markdown_**. 
 
I can’t believe I’ve been logging all of this time without using markdown or HTML, so I’ve been going through cleaning and spicing things up. Plus, I found a ton of errors including most of my Twitter links not properly displaying as hyperlinks. I almost contemplated leaving my log as is and keeping it pure and raw... naahh. Mighty Joe needs his content to be presentable. Plus, you can just look at the history if you really want to experience *the raw* :wink:.

If you are wanting to learn or refresh your markup skills for Github, the following links were very helpful to me:
1. [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
2. [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
3. [Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet/)

**Link to tweet** [MightyJoeW Day 99](https://twitter.com/MightyJoeW/status/870063111406993408)

<h2 align="center">Day 100: Thursday June 01, 2017</h2>

<p align="center">
<img src="http://www.ounewsbureau.com/wp-content/uploads/2013/02/finish-line.jpg" alt="Finish Line Ahead">
</p>
<br>
<p align="center"><b>Today's Progress:</b> Reviewing code and continued upgrading this log into a unique visual experience</p>

#100DaysOfCode has been an absolutely wonderful experience, and I sincerely thank Alex Kallaway for creating this challenge (and CodeNewbie for interviewing him). 
 
These 100+ days have been a roller coaster complete with ups, downs, twists, and turns. Although it has been an unpredictable journey, one thing that was consistent was well... consistency. I made it to somewhere in the 80s without missing a day as this challenge created a routine for me. No matter how I felt or how late it was, I was going to get in an hour of code. It takes dedication and consistency to see a difference, and I owe a lot of my progress to this challenge.
 
There came a stretch where I had to tend to other things then couldn’t get quite back in my groove, but the challenge brought me back. I **had** to finish. Coming back to finish also got me working on some other projects that were more enjoyable which brought that spark back (Javascript algorithms beat me down lol).
 
These 100 Days of coding led me to live meetups, online courses, new friends, and so much more. I’ve been exposed to many different programming languages and practices, and I gained a clearer idea of what I am wanting to focus on.

<img src="https://lh3.googleusercontent.com/AVUZpVhbPHVxLmMLG5rwTdqv6jGGJ9aVIER3dKkiNvVN0n6B8e1HJDvK5eNIxnLii7EOgbCDIMRApUIz_8I3V0wHn9BB54cY19Gy4oih8X6YQg4mGjt3OG6y476bcsYmiwyckP1lubtU3wobKRcRG5qgRuPYiNaFCBLyhyoFXmUaGUgnI7XwSybAurj7u7VmEibv_Z9O8zliMAqXyur4j05kDKD96Ay9GvGROjrgROYPiZZg8CxaYdNNQN6PkvvA1w4vfXDgZQIwjZnxjofa4mQ4izxxbSqyIwsRFZ9GGgXp5he641WyKaych9ckPOLQRrSr3tz-unQ0EGR2QYp5vOxqjfRrJNWhO7CAewyt9T5VzC7FInHCmogtfEvJqnkU1eyp0xMwmMh_lXZfkFyUgbyYYEm4fuaySfMh2HPh8PKOjld3ySMZjeBZjl3MyN8BLIBS85OTrNL-LKDVi1cidb7peejfRMZotsDbLUnna3VYa55LuZgTl8hhelfdivquXp3-cFMYRsq3IIpU-5amDVdifZ3m06MCm1dYV0kf461_XN-aI1-U3Iv3Qf3UI2Es1t_8xdg1if6v55TAHesnd-wvmTW2e8ndIt1FSe4CMaySXTJdLetLCg=w791-h582-no" alt="fCC Study Group of the Day - Dallas">
 
As I wrap up this journey, I look forward to embarking on the next one as this is only the beginning. I plan to write an article and submit it to Medium. I have some tech conferences next week that I am really exciting about (including one early tomorrow morning). I am hoping to give a talk this summer at a tech conference in Austin. I have _tons_ of projects that I’d like to finish and post on Github. Our Free Code Camp group is starting on some open source projects. And I still want to make an Arduino Magic Mirror dangit!
 
Thank you for your time. I hope you enjoyed experiencing this with me, and I wish you the very best on your journey.
 
Sincerely, 
Joe

**Link to tweet:** [MightyJoeW Day 100](https://twitter.com/MightyJoeW/status/870484699776401409)

**Link to work:** Scroll up :wink:
