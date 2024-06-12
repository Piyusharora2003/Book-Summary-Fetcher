# Book Summary Fetcher

This new system fetches book summaries based on user queries, generates keywords to refine the search, and produces book-related advice. The access control mechanism manages actions like viewing, editing, and deleting data based on user roles. The Gradio interface provides a simple web-based UI for testing access control.


## Usage

1. Run the script using `python app.py`.
2. Access the application through a Gradio interface to check access control permissions based on user role and action.
3. Enter the user role and action you want to check permissions for.
4. Review the output to see if permission is granted or denied for the specified action.


## Dependencies

- `haystack`
- `gradio`
- `requests`
- `opal`

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request.
