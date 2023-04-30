```php
<?php wp_head(); ?> //Prints scripts or data in the head tag on the front end
```

```php
<?php wp_footer(); ?> //Prints scripts or data before the closing body tag on the front end.
```

```php
<?php body_class(); ?> //allows you to assign CSS classes to the body element
```

```php
<?php bloginfo(); ?> //Displays information about your site, mostly gathered from the information you supply in your User Profile and General Settings WordPress Administration Screens
```

```php
//loop

<?php if( have_posts() ) : while( have_posts() ) : the_post(); ?>
  <?php endwhile; else : ?>
  <p> <?php esc_html_e( 'There is no posts' ); ?> </p>
  <?php endif; ?>
```

```php
<?php the_ID(); ?> //returns every object's “identity.”
```

```php
<?php the_permalink(); ?> //Displays the permalink for the current post.
```

```php
<?php the_title(); ?> //a filter applied to the post title retrieved from the database, prior to printing on the screen.
```

```php
<?php esc_html_e(); ?> //Displays translated text that has been escaped for safe use in HTML output.
```

```php
<?php get_header(); ?> //Includes the header template for a theme or if a name is specified then a specialized header will be included.
```

```php
<?php get_footer(); ?> //Includes the footer template for a theme or if a name is specified then a specialized footer will be included
```