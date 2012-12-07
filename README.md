day-cq-searchable
=================

Installation steps:

1. Start a CQ instance (5.4+)
2. Check out the git repository and navigate to <day-cq-searchable>/jcr_root
3. Import the application. The command is something like this: vlt --credentials admin:admin import -v http://localhost:4502/crx . /
4. Open: http://localhost:4502/cf#/content/selectable-sample.html
If it works fine you should see a list about the products of the geometrixx...