# jules-hello

A minimal Python "Hello, World" project.

## Running the code

To run the application, execute the following command:

```bash
python hello.py
```

## Running the tests

To run the tests, you first need to install pytest:

```bash
pip install pytest
```

Then, you can run the tests with:

```bash
pytest
```

The tests will run in quiet mode by default, as configured in `pytest.ini`.

## Jules-driven workflow
- Create an Issue using the template:
  https://github.com/sai00sin/jules-hello/issues/new?template=jules-task.yml&labels=jules&title=%5BJules%5D%20New%20task
- The Issue gets label `jules`, then Jules plans → opens a PR.
- To stop a run: remove the `jules` label or close the Issue.
- All PRs must be green (CI) before merge.

Notes:
- If GitHub Actions is disabled, please enable it in the repository's Actions tab so CI can run.