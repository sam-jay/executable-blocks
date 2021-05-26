# executable-blocks
Literate programming environment that integrates with Notion-like block oriented note taking applications.


Alpha Roadmap:
* Implement `read_block :: BlockId -> IO Maybe BlockContent`
* Implement `write_block :: BlockId -> BlockContent -> IO Result`
* Implement `is_executable :: BlockContent -> Bool`
* Implement `parse_block :: BlockContent -> Executable`
* Implement `execute :: Executable -> State -> IO Result`
* Implement Executor
* Implement UI for monitoring executions.
* Programmatically make content updates to a notion block

