# `@angle-measurer/page-interactors`

Contains `browser` and `element` libraries which implement their own interfaces, and differ in being singletons with static methods (which are never replaced, and thus avoid race conditions).

The underlying mechanisms belonging to particular concretions may do whatever is necessary to work, but the APIs should provide access (standard or framework specific), to DOM (real or virtual) interaction through whatever means is necessary.