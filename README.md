<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<h1>Quick-Start Laravel E-commerce Application</h1> 
    <p>To start the Laravel e-commerce application you downloaded from GitHub on your local machine, you can follow these steps:</p>
    <ol>
      <li>Open a terminal or command prompt and navigate to the root directory of the project.</li>
      <li>Run the following command to install the required dependencies:</li>
    </ol>
    <pre><code>composer install</code></pre>
    <ol start="3">
      <li>Next, create a copy of the <code>.env.example</code> file and rename it to <code>.env</code>:</li>
    </ol>
    <pre><code>cp .env.example .env</code></pre>
    <ol start="4">
      <li>Generate a new application key:</li>
    </ol>
    <pre><code>php artisan key:generate</code></pre>
    <ol start="5">
      <li>Set up your MySQL database by editing the database configuration in the <code>.env</code> file. You'll need to set the <code>DB_HOST</code>, <code>DB_PORT</code>, <code>DB_DATABASE</code>, <code>DB_USERNAME</code>, and <code>DB_PASSWORD</code> variables.</li>
      <li>Run the database migrations to create the necessary tables:</li>
    </ol>
    <pre><code>php artisan migrate</code></pre>
    <ol start="7">
      <li>Finally, start the development server:</li>
    </ol>
    <pre><code>php artisan serve</code></pre>
    <p>This will start the application and you can access it by opening your web browser and navigating to <a href="http://localhost:8000">http://localhost:8000</a> (or a different port if specified in the <code>php artisan serve</code> command).</p>





</p>
Laravel DocS https://laravel.com/docs/9.x/
