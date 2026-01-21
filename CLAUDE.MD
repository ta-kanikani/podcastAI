# PodcastAI

An AI-powered podcast generation and management system.

## Project Overview

This project leverages artificial intelligence to create, manage, and enhance podcast content.

## Project Structure

```
podcastAI/
├── CLAUDE.MD          # This file - project documentation for AI assistance
├── src/               # Source code
├── tests/             # Test files
├── docs/              # Documentation
└── scripts/           # Utility scripts
```

## Technology Stack

To be determined based on project requirements.

## Development Guidelines

### Code Style
- Write clean, readable, and maintainable code
- Follow language-specific best practices
- Add comments for complex logic
- Use meaningful variable and function names

### Testing
- Write tests for new features
- Maintain high test coverage
- Run tests before committing

### Git Workflow
- Create feature branches for new work
- **コミットメッセージは1行の日本語でシンプルに記載してください**
- Write clear, descriptive commit messages (in Japanese, one line)
- Keep commits focused and atomic

## Working with Claude Code

### 基本方針

**重要: このプロジェクトでは、常に日本語で回答してください。**

**IMPORTANT: Always respond in Japanese when working on this project.**

- **ユーザー情報**: ユーザー名は「t」で、開発初心者です
- **説明スタイル**: 分かりやすく解説し、技術スキルを教育するような丁寧な説明を心がけてください
- **プロジェクト目標**: 自動開発を最終的な目標としています
- **技術スタック**: LLMアプリケーションなどの最新技術を用いたWebアプリ開発が中心です
- **最新情報の参照**: Web検索やMCPサーバーを積極的に活用し、最新のドキュメントや情報を参照してください
- **手作業の最小化**: 自動化できる部分は自動化し、手作業は最小限に抑えてください

### Claude Code運用のベストプラクティス

1. **サブエージェントの活用**
   - コンテキスト節約のため、調査やデバッグにはサブエージェントを積極的に活用してください
   - 複雑なタスクは適切なサブエージェントに委譲しましょう

2. **記憶喪失対策**
   - 会話が長引くとスレッドが圧縮要約されて記憶喪失になる可能性があります
   - 自動圧縮がかからないうちに、定期的に重要な点をマークダウンファイルとしてプロジェクトディレクトリ内に保存・更新してください
   - 開発の進捗、設計決定、技術的な課題などを適宜ドキュメント化しましょう

3. **機密情報の管理**
   - 開発中に生成するドキュメントにAPIキーなどの機密情報を書いても構いません
   - ただし、機密情報を含むファイルは**必ず `.gitignore` に追加**してください
   - セキュリティを常に意識した開発を行いましょう

4. **一般的なベストプラクティス**
   - **Be Specific**: 明確な要件とコンテキストを提供してください
   - **Iterative Development**: 機能を段階的に構築していきます
   - **Review Changes**: コミット前に生成されたコードを必ず確認してください
   - **Ask Questions**: 不明点があれば遠慮なく質問してください

## Key Features (Planned)

- AI-powered podcast content generation
- Audio processing and enhancement
- Transcript generation
- Content summarization
- Multi-voice synthesis
- Episode management

## Getting Started

Instructions for setting up the development environment will be added as the project develops.

## Architecture Decisions

Document architectural decisions and technical choices here as the project evolves.

## API Integrations

- TTS (Text-to-Speech) services
- Speech recognition
- AI language models
- Audio processing libraries

## Performance Considerations

- Optimize audio processing pipelines
- Implement caching strategies
- Handle large file uploads efficiently
- Consider asynchronous processing for long-running tasks

## Security Notes

- Sanitize user inputs
- Secure API keys and credentials
- Implement rate limiting
- Validate file uploads

## Future Enhancements

- Multi-language support
- Custom voice training
- Advanced audio editing features
- Automated publishing workflows
- Analytics and insights

---

**Last Updated**: 2026-01-21
**Maintained By**: Project Team
