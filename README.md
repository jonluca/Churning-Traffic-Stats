# Churning-Traffic-Stats

Data and code for quarterly analysis of traffic to /r/churning

## Usage

Create a file `account.py` with the following format:

```python
mod_username = "username"
mod_password = "password"
mod_script_id = "id"
mod_script_secret = "secret"
```

## File layout

The arrays in the "days" array is laid out like: [epoch time, uniques, pageviews, subscriptions]

The arrays in both the "hours" and "months" arrays are laid out like: [epoch time, uniques, pageviews]