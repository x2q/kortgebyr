KORTGEBYR
============

Udviklet af Ulrik Moe, Christian Blach og Joakim Sindholt.

Kortgebyr er en dansk prissammenligningsside for betalingsløsninger og betalingsgateways. Siden er skrevet i Javascript og hostet på Amazon S3. Formålet med siden er at gøre markedet for betalingsløsninger overskueligt og forståeligt for den gennemsnitlige iværksætter.


Installer lokalt
============

Det er nemt at bidrage til projektet. Du skal blot installere Grunt via npm, som er en package manager der følger med <a href="http://nodejs.org/download/">Node.Js</a>.

<pre>
npm install -g grunt-cli
</pre>

Når GruntJS er installeret skal du blot, udgangspunkt fra folder <code>cd kortgebyr</code>, køre følgende komando:

<pre>
npm install
</pre>

npm installerer alle nødvendige pakker (devDependencies i Package.json). Nu skal du bare køre følgende og så skulle din browser gerne åbne en side til webserven med autoreload (livereload) enabled.
<pre>
grunt server watch
</pre>


LICENSE
============
Koden er udgivet under [a relative link](GPLv3.md). Alle logoer og kortikoner tilhører de respektive ejere.
