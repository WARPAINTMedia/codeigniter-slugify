# codeigniter-slugify

A helper for CodeIgniter to create nice slugified urls and filenames.

### Installation

Save this script to `application/helpers/` or wherever you are loading helpers. If this is for PyroCMS, you would put this in `pyrocms/addons/shared_addons/helpers/`

### Using the Helper

This can be in your *controller*, *model*, or *view* (not preferable).

```php
$this->load->helper('slugify');
```

If you use this helper in a lot of locations you can have it load automatically by adding it to the autoload configuration file.

```php
$autoload['helper'] = array('slugify');
```

### Usage

Input

```php
echo slugify('My Title That Needs To Be A Nice URL!');
```

Output

```
my-title-that-needs-to-be-a-nice-url
```